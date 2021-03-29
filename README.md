# liquibase-ext-schema

### Overview
Liquibase schema, which contains all custom tags, attributes and xml types used by custom Liquibase extension (see `liquibase-ddm-ext` repository for details).

### Usage
Add a reference to `dbchangelog-ddm.xsd` to your Liquibase changelog file.
Example:
```bash
<databaseChangeLog
    xmlns="http://www.liquibase.org/xml/ns/dbchangelog"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xmlns:ext="http://www.liquibase.org/xml/ns/dbchangelog-ext"
    xsi:schemaLocation="http://www.liquibase.org/xml/ns/dbchangelog http://www.liquibase.org/xml/ns/dbchangelog/dbchangelog-4.5.xsd
    http://www.liquibase.org/xml/ns/dbchangelog-ext dbchangelog-ddm.xsd">
```

### Licensing
The liquibase-ext-schema is Open Source software released under the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0).