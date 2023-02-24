# Naming convention

|         | Scale       | Object           | Naming               | Details                         | Example                                |
| ------- | ----------- | ---------------- | -------------------- | ------------------------------- | -------------------------------------- |
| Backend | DB          | Table name       | Snake case, singular | Entity related, model related.  | vehicle, vehicle_type, vehicle_account |
| Backend | DB          | ID, Primary key  | id                   |                                 | id                                     |
| Backend | DB          | Foreign key      | `id_<name>`          | name - name of referenced table | id_vehicle, id_vehicle_type            |
| Backend | Application | Model class name | Camel case, singular | Entity related, table related   | VehicleType, VehicleAccount            |


