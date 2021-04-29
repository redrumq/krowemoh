
## README.md
####  README.md


if you want to go to test.md
click https://github.com/redrumq/krowemoh/blob/b2bd1ee1b7596e68321b0e8aa9e4059002609d9d/test.md

---


网络图片：

![网络图片](http://i0.hdslb.com/bfs/article/125d882c379c965539fb528f31bdfc8c24713a82.jpg)



---


github文件夹下的一张图片:

![avatar](https://github.com/redrumq/krowemoh/blob/28e21ffb9dccee9695ac458110211afc440642c8/ddd.png)


---


an externalweb site:
<https://www.baidu.com/>



---




a block quote:
>redrumq
> > kpachnar
> > > kgb


---



 a bulleted list:
+ mike
+ tommy
+ rockstars
+ gta
+ steep
+ red dead redemption 2


---



a numbered list:


1. test1：
    - shoes
    - apple
2.test2：
    - origin
    - ea
    - steam
    - ubisoft
3.test3：
    -google
    -microsoft
    -bytedance
    
    
 ---
    
 


a table:

| 省   | 省会  |
|  ----  | ----  |
| 吉林  | 长春 |
| 辽宁  | 沈阳 |
| 山东  |  济南|



---


**粗体文本**

*斜体文本*

~~删除线文本~~



---

```java
private void requestPermission() {
        if (Build.VERSION.SDK_INT >= 23 && !isPermissionRequested) {
            isPermissionRequested = true;
            ArrayList<String> permissionsList = new ArrayList<>();
            String[] permissions = {
                    Manifest.permission.ACCESS_NETWORK_STATE,
                    Manifest.permission.INTERNET,
                    Manifest.permission.WRITE_EXTERNAL_STORAGE,
                    Manifest.permission.READ_EXTERNAL_STORAGE,
                    Manifest.permission.ACCESS_COARSE_LOCATION,
                    Manifest.permission.ACCESS_FINE_LOCATION,
                    Manifest.permission.ACCESS_WIFI_STATE,
            };

            for (String perm : permissions) {
                if (PackageManager.PERMISSION_GRANTED != checkSelfPermission(perm)) {
                    permissionsList.add(perm);
                    // 进入到这里代表没有权限.
                }
            }

            if (!permissionsList.isEmpty()) {
                String[] strings = new String[permissionsList.size()];
                requestPermissions(permissionsList.toArray(strings), 0);
            }
        }
    }
    
    ```
    
    
    



    







