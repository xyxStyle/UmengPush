# 友盟推送

技术交流群：598627802，加群前请务必阅读[群行为规范](https://github.com/Lee-Wang-Jing/GroupStandard)
有问题或者某种需求欢迎加群或者提issues，Thanks
----
# Features
1. 友盟推送


# Dependencies
* Gradle
```groovy
compile 'com.xyx:umengpush:1.0.0'
```
* Maven
```xml
<dependency>
  <groupId>com.xyx</groupId>
  <artifactId>umengpush</artifactId>
  <version>1.0.0</version>
  <type>pom</type>
</dependency>
```

* Eclipse ADT请放弃治疗


## AndroidManifest中添加
```
    <meta-data
        android:name="UMENG_APPKEY"
        android:value="${UMENG_APPKEY}"/>
    <meta-data
        android:name="UMENG_MESSAGE_SECRET"
        android:value="${UMENG_MESSAGE_SECRET}"/>
    <meta-data
        android:name="UMENG_CHANNEL"
        android:value="Umeng"/>
```

# License
```text
Copyright 2017 xyx

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.