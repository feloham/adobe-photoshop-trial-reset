# Adobe Photoshop Trial

This one is for study purposes and demonstration how easy is to bay-pass trial period on Photoshop. With this little "app" you can extend your photoshop trial period. Or you can follow the explanation and do it manually.

## How Does It Work
All you have to do, to extend your trial period, is change number in TrialKey element in application.xml. This file is located 
in
```
/Library/Application Support/Adobe/Adobe Photoshop/AMT
```

It is in TrialSerialNumber Data key:
```
<Data key="TrialSerialNumber">911997074887979240115317</Data>
```

And increment this number by one:
```
<Data key="TrialSerialNumber">911997074887979240115318</Data>
```

And that's it!
