## <font color="#F2853F" style="font-size:24pt">ble\_gap\_adv\_set\_data</font>

```c
int
ble_gap_adv_set_data(
    const uint8_t *data,
              int  data_len
)
```

### Description

Configures the data to include in subsequent advertisements.

### Parameters

| *Parameter* | *Description* |
|-------------|---------------|
| data | Buffer containing the advertising data. |
| data\_len | The size of the advertising data, in bytes. |

### Returned values

| *Value* | *Condition* |
|---------|-------------|
| 0 | Success. |
| BLE\_HS\_EBUSY | Advertising is in progress. |
| [Core return code](../../ble_hs_return_codes/#return-codes-core) | Unexpected error. |
