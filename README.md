# Media-WebLink
- Mac update weblink
	- `grep -r "7xudfs.com1.z0.glb.clouddn.com" * | awk '{print $1}' | grep -v Binary| awk -F : '{print $1}' | uniq | xargs -I{} sed -i.wenwbackupnotexist 's/http:\/\/7xudfs.com1.z0.glb.clouddn.com/https:\/\/raw.githubusercontent.com\/wu-wenxiang\/Media-WebLink\/master\/qiniu/' {}`
	- `find ../github-mine | grep wenwbackupnotexist | xargs -I{} rm -rf {}`
- Weblink: `https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/`	
