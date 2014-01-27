Add
```
import /init.superuser.rc
```
to `system/core/rootdir/init.rc`.

Add
```
PRODUCT_PACKAGES += \
    Superuser \
    su
```
to `build/target/product/generic_no_telephony.mk`.
