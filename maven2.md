
```
            <dependency>
                <groupId>net.sf.bluecove</groupId>
                <artifactId>bluecove</artifactId>
                <version>2.1.0</version>
            </dependency>

            <!-- If you plan to run application on Linux -->
            <dependency>
                <groupId>net.sf.bluecove</groupId>
                <artifactId>bluecove-gpl</artifactId>
                <version>2.1.0</version>
                <scope>runtime</scope>
            </dependency>

            <!-- If you plan to test your application in emulated Bluetooth mode -->
            <dependency>
                <groupId>net.sf.bluecove</groupId>
                <artifactId>bluecove-emu</artifactId>
                <version>2.1.0</version>
                <scope>test</scope>
            </dependency>            
```


> If you are building MIDlet application change _scope_ to _provided_

```
            <dependency>
               <groupId>net.sf.bluecove</groupId>
               <artifactId>bluecove</artifactId>
               <version>2.1.0</version>
               <scope>provided</scope>
            </dependency>
```

> We recommend that you use [MicroEmulator](http://www.microemu.org/) together with BlueCove for development and debugging J2ME MIDlet applications.