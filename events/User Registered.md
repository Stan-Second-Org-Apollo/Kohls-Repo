# User Registered

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Registered",
    "user": {
        "sephora": {
            "phoneProvided": "<phoneProvided>",
            "registration": "<registration>",
            "zipProvided": "<zipProvided>"
        }
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|phoneProvided|boolean|Customer hit the "success" page after signing up for BI and provides their phone number during setup||||||||
|registration|boolean|Customer hit the "success" page after signing up for BI.||||||||
|zipProvided|boolean|Customer hit the "success" page after signing up for BI and provides their zip code during setup||||||||
