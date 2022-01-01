1.
download và install cái này
https://aws.amazon.com/cli/ </br>
1a.
Install hugo. On window, install Chocolatey with Administrative PowerShell (https://chocolatey.org/install)
After installing chocolatey, type choco install hugo. </br></br>

2. 
mở Administrative Powershell. nhập aws configure </br>
Access Key ID: AKIA46UJRR64GFXEEWWH </br>
Secret Access Key = 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 </br>
Default region = ap-southeast-1 </br>
Default output format = json </br>

3. 
download this repo either as zip or using git pull và chỉnh sửa image </br>
mỗi lần chỉnh sửa image xong, nhập hugo với hugo deploy để chỉnh website. </br>
nhập hugo server -D và và nhập localhost:1313 trên chrome để preview website. </br>

4. 
To create new post, copy over a folder from /content/post (preferrably deluxe-room). Edit the content in index.md. Photo with caption can be inserted like this: </br>
![caption here](name of the image here) </br>
Remember that you must put all images in the same folder as the index.md </br>
