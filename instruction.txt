1. download và install cái này
https://aws.amazon.com/cli/
1a.
Install hugo. On window, install Chocolatey with Administrative PowerShell (https://chocolatey.org/install)
After installing chocolatey, type choco install hugo.

2.
mở Administrative Powershell. nhập aws configure
Access Key ID: AKIA46UJRR64GFXEEWWH 
Secret Access Key = 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
Default region = ap-southeast-1
Default output format = json


3. download website và chỉnh sửa image
mỗi lần chỉnh sửa image xong, nhập hugo với hugo deploy để chỉnh website.
nhập hugo server -D và và nhập localhost:1313 trên chrome để preview website.

4. To create new post, copy over a folder from /content/post (preferrably deluxe-room). Edit the content in index.md. Photo with caption can be inserted like this:
![caption here](name of the image here)
Remember that you must put all images in the same folder as the index.md