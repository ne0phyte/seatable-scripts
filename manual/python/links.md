# Links

This document will show how to manipulate links through the Base object

If you do not yet understand the Base object, please refer to this document

* [Base](base.md)


#### add link

Add links, link other table records

```python
# link_id: link_id in the data attribute of the link column
# table_name: The name of the link table
# other_table_name: The name of the linked table
# row_id: id of the link row
# other_row_id: id of the linked row
base.add_link(link_id, table_name, other_table_name, row_id, other_row_id)
```

##### Example

```python
base.add_link('5WeC', 'real-img-files', 'contact', 'CGtoJB1oQM60RiKT-c5J-g', 'PALm2wPKTCy-jdJNv_UWaQ')
```

#### remove link

Delete the link row

```python
# link_id: link_id in the data attribute of the link column
# table_name: The name of the link table
# other_table_name: The name of the linked table
# row_id: id of the link row
# other_row_id: id of the linked row
base.remove_link(link_id, table_name, other_table_name, row_id, other_row_id)
```

##### Example

```python
base.remove_link('5WeC', 'real-img-files', 'contact', 'CGtoJB1oQM60RiKT-c5J-g', 'PALm2wPKTCy-jdJNv_UWaQ')
```
