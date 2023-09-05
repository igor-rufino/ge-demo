# Python & Great Expectations [GE]

### install great expectations
```shell
pip install great_expectations
great_expectations --version
```

### add data context
```shell
great_expectations init
```

### add data source
```shell
great_expectations datasource new
data
```

### add expectations [data docs]
```shell
great_expectations suite new

# "passenger_count" = comment
```

### validate data [checkpoint]
```shell
great_expectations checkpoint new checkpoint_01_ge_suite_yellow_tripdata

# data_asset_name: yellow_tripdata_sample_2019-02.csv
```