repa
====

A password management tool that uses reop to store credentials

# Usage

## repa init

```
repa init [-s [store_name]]
```

Initialize a new named pub/priv key pair and database. [store_name] is optional, and by default `repa` is used.

## repa add

```
repa add entry_name [-s [store_name]]
```

Adds an entry named `entry_name` to `store_name` or `repa` if `store_name` is not specifieid.

## repa find

```
repa find "string" [-s [store_name]]
```

Searches for "string" in either the default store, or a named store.

## repa show

```
repa show entry_name [-s [store_name]]
```

Dumps a given `entry_name`, showing all information associated with a given entry.

## repa gen

```
repa gen [-s [store_name]]
```

Generates a new random password, if `add_generated` is configured, this will further prompt the user for more information and add a new entry.

## repa edit

```
repa edit [-s [store_name]] entry_name
```

Edit an existing entry.

## repa delete

```
repa delete [-s [store_name]] entry_name
```

## repa dump

```
repa dump
```

Dumps the entire database to STDOUT

Delete an entry.
