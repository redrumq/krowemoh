## test
#### code


**粗体文本**

*斜体文本*

~~删除线文本~~


| 省   | 省会  |
|  ----  | ----  |
| 吉林  | 长春 |
| 辽宁  | 沈阳 |
| 山东  |  济南|





>redrumq
> > kpachnar
> > > kgb




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
  
    
+mike
+ tommy
+ rockstars
+ gta
+ steep
+ red dead redemption 2

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

if you want to go to README.md
click https://github.com/redrumq/krowemoh/blob/5c45f9a55ad7543eabff055764150a8764fb7a4f/README.md
