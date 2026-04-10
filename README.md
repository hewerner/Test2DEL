# OpenCDC Record Spec

CDC-OIS, a vendor-neutral JSON format for change data capture event streams. CDC-OIS uses CloudEvents v1.1 as its envelope layer, combined with a GoldenGate-derived payload design hardened for cross-platform interoperability. The standard mandates self-describing, schema-inline streams that are independently consumable without external infrastructure dependencies. It defines canonical representations for DML operations, DDL events, transaction identity, schema evolution, and stream lifecycle events across heterogeneous database sources.

The following are some examples of CDC_OIS payload.


## Metadata Record

metadata_payload.json

## Update DML Record

update_payload.json

## Truncate Table DDL Record

ddl_truncate_payload.json

## Alter Table DDL Recrod

ddl_alter_table_payload.json
