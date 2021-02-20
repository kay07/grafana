# grafana
由于k8s部署grafana默认没有对数据进行持久化，即重启会导致grafana配置的数据丢失，这里对grafana进行了mysql的数据持久化。

配置说明：

在grafana-conf.yaml文件中需要指定数据源，第83-87行，提前并且创建名为grafana的数据库，并配置相应的数据库信息即可。
