## doora
doora is the Oracle JDK installer for GNU / Linux users with Debian distribution. It is intended for users who do not prefer PPA installation and to simplify the complexity of manual installation. It is very simple to use and does not require any dependence. Just download the doora script.

### Oracle JDK
Download Java SE Development Kit of your choice from oracle.com.
The file extension must be `.tar.gz.`

### Download doora
```sh
$ git clone https://github.com/dootec/doora
```

### Installation JDK
```sh
$ sudo ./doora jdk-12.0.1_linux-x64_bin.tar.gz
```

The script will ask you for the file name to be sure, you can enter the following command from the beginning to skip these steps quickly. Of course, this command is optional, you can not use if you want.
```sh
$ sudo ./doora jdk-12.0.1_linux-x64_bin.tar.gz -y
```

### Successful Installation Message

```sh
Congratulations, Oracle JDK installation completed successfully!

New JDK Details:
java version "12.0.1" 2019-04-16
Java(TM) SE Runtime Environment (build 12.0.1+12)
Java HotSpot(TM) 64-Bit Server VM (build 12.0.1+12, mixed mode, sharing)
javac 12.0.1

Have a nice day.
```
