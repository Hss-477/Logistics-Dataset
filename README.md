### Scenario Description

This dataset captures the process of trucks loading goods at a factory, recording the following stages:
              queueing outside the factory → entering the factory→ queueing outside the warehouse → entering the warehouse for loading → leaving the factory.

The number of parking spots available outside different warehouses varies, and the loading time required for different goods is not the same. The dataset comprises three tables that record information about the warehouses, goods, and the status of the trucks.

### Table Description

1. cargo_info.csv 

   This file records the time required for loading different types of cargo. There are 15 types of cargo in total.

2. warehouse_info.csv  

   This file documents the number of parking spots available outside each warehouse and the types of cargo stored inside. There are 50 warehouses in total.

3. queuing_info.csv 

   This file tracks the status changes of trucks arriving at the factory over a three-month period. There are 89,499 truck records for January and February combined, and 30,790 truck records for March.
