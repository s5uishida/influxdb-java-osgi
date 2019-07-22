# influxdb-java-osgi
This repository contains the MANIFEST.MF file of **the Eclipse plug-in project** for building OSGi bundle from the [influxdb-java-2.15](https://github.com/influxdata/influxdb-java/tree/influxdb-java-2.15) of [influxdb-java](https://github.com/influxdata/influxdb-java) and the built bundle file. You need Java 8 or higher.

I use this with the following bundles.
- [OkHttp 3.14.1](https://github.com/square/okhttp/tree/parent-3.14.1)  
I use the pre-built [org.apache.servicemix.bundles.okhttp-3.14.1_1.jar](https://mvnrepository.com/artifact/org.apache.servicemix.bundles/org.apache.servicemix.bundles.okhttp/3.14.1_1) provided by [MVN Repository](https://mvnrepository.com/)

- [Okio 1.15.0](https://github.com/square/okio/tree/okio-parent-1.15.0)  
I use the pre-built [org.apache.servicemix.bundles.okio-1.15.0_1.jar](https://mvnrepository.com/artifact/org.apache.servicemix.bundles/org.apache.servicemix.bundles.okio/1.15.0_1) provided by [MVN Repository](https://mvnrepository.com/)

- [Retrofit 2.5.0](https://github.com/square/retrofit/tree/parent-2.5.0)  
I use the pre-built [org.apache.servicemix.bundles.retrofit-2.5.0_2.jar](https://mvnrepository.com/artifact/org.apache.servicemix.bundles/org.apache.servicemix.bundles.retrofit/2.5.0_2) provided by [MVN Repository](https://mvnrepository.com/)

- [Moshi 1.7.0](https://github.com/square/moshi/tree/moshi-parent-1.7.0)  
I use the pre-built [moshi-osgi_1.7.0.jar](https://github.com/s5uishida/moshi-osgi).

- [MessagePack for Java 0.8.17](https://github.com/msgpack/msgpack-java/tree/0.8.17)  
I use the pre-built [msgpack-core-osgi_0.8.17.jar](https://github.com/s5uishida/msgpack-core-osgi).

I would like to thank the authors of this very useful influxdb-java code, and all the contributors.
