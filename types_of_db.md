**DragonFly - CP**

Это база данных основана на Redis.
В свою очередь Redis является CP
https://aws.amazon.com/ru/redis/
https://www.bigdataschool.ru/wiki/cap

также:

**C**: DragonFly используют для транзакций, поэтому она обязана быть согласованной

**P**: в DragonFly при отказе какого-то количества узлов остальные продолжают функционировать в силу многопоточной архитектуры без разделения ресурсов
https://www.opennet.ru/opennews/art.shtml?num=57279

**ScyllaDB - АP**

Scylla chooses availability and partition tolerance over consistency
https://docs.scylladb.com/stable/
https://docs.scylladb.com/stable/architecture/architecture-fault-tolerance.html

**Arenadata - CA**

**C**: Arenadata используют для транзакций, поэтому она обязана быть согласованной

**A**: не уверена, основана на greenplum, она кажется А
https://greenplum.org/learn/
https://arenadata.tech/wp-content/uploads/2020/06/arenadata-db-1.pdf


по CAP теореме в каждом случае 3-го быть не может