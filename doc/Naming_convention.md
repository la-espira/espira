# Naming convention

|         | Scale       | Object           | Naming                      | Details                         | Example                                      |
| ------- | ----------- | ---------------- |-----------------------------| ------------------------------- |----------------------------------------------|
| Backend | DB          | Table name       | `t_` + Snake case, singular | Entity related, model related.  | t_vehicle, t_vehicle_type, t_vehicle_account |
| Backend | DB          | ID, Primary key  | id                          |                                 | id                                           |
| Backend | DB          | Foreign key      | `id_<name>`                 | name - name of referenced table | id_vehicle, id_vehicle_type                  |
| Backend | Application | Model class name | Camel case, singular        | Entity related, table related   | VehicleType, VehicleAccount                  |
