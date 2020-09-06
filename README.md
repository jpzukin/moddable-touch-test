# moddable-touch-test
タッチセンサを確認をするだけ（FT6206）

タッチセンサが読み取った値は、xsbugのLOGにしか出力しないので、デバッグモードでのビルドが必須です。

```
mcconfig -m -d -p m5stack_core2
```
