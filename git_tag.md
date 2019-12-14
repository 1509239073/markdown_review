**1.显示所有的tag**  

`git tag`  

**2.查看某个版本系列的tag**

`git tag -l 'v1.0.*'`

**3.创建标签**

`git tag -a v1.0.0 -m "内容：v1.0.0"`

**4.查看标签的详情，可以看到你commit的内容**

`git show v0.0.6`

**5.推送标签**

`git push origin v1.0.0`

**6.删除标签** 
* 删除本地  
 `git tag -d v1.0.0`
* 删除远程的  
`git push origin :refs/tags/v1.0.0`

