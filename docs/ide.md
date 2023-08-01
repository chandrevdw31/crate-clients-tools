(ide)=

# Using database IDEs with CrateDB

Mostly through its PostgreSQL interface, CrateDB supports working with popular
database IDE (Integrated Development Environment) applications.

## DataGrip

```{div}
:style: "float: right"
[![](https://blog.jetbrains.com/wp-content/uploads/2019/01/datagrip_icon.svg){w=120px}](https://www.jetbrains.com/datagrip/)
```

[DataGrip] is a cross-platform database IDE that is tailored to suit the specific needs
of professional SQL developers.

Connection to DataGrip works by using the vanilla PostgreSQL JDBC Driver, the blog
article [Blog: Use CrateDB With DataGrip] explains how it works. 

![](https://19927462.fs1.hubspotusercontent-na1.net/hub/19927462/hubfs/13-Datagrip.png?width=1536&name=CrateDB-DataGrip.png){h=200px}
![](https://19927462.fs1.hubspotusercontent-na1.net/hub/19927462/hubfs/16-Datagrip.png?width=1536&name=16-Datagrip.png){h=200px}


## DBeaver

```{div}
:style: "float: right"
[![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/DBeaver_logo.svg/512px-DBeaver_logo.svg.png){w=120px}](https://dbeaver.io/)
```

DBeaver is a multipurpose database tool for developers and database administrators.
Because CrateDB provides a JDBC driver, you can access CrateDB with any client tool that supports JDBC drivers.

Connection to DataGrip works by using the legacy PostgreSQL JDBC Driver, the blog
article [Blog: Use CrateDB With DBeaver] explains how it works. 

![](https://19927462.fs1.hubspotusercontent-na1.net/hub/19927462/hubfs/Screen-Shot-2019-04-05-at-17.13.21.png?width=1600&name=CrateDB-DBeaver.png){h=200px}
![](https://19927462.fs1.hubspotusercontent-na1.net/hub/19927462/hubfs/Screen-Shot-2019-04-05-at-17.15.13.png?width=1600&name=Screen-Shot-2019-04-05-at-17.15.13.png){h=200px}


[Blog: Use CrateDB With DataGrip]: https://crate.io/blog/use-cratedb-with-datagrip-an-advanced-database-ide
[Blog: Use CrateDB With DBeaver]: https://crate.io/blog/cratedb-dbeaver
[DataGrip]: https://www.jetbrains.com/datagrip/
[DBeaver]: https://dbeaver.io/