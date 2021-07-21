# Two-Factor Authentication Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Two-Factor Authentication Started",
    "user": {
        "sephoraEmailFound": "<sephoraEmailFound>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|sephoraEmailFound|boolean|After performing a search for their Beauty Insider account, the system finds a match and takes them to the One Time Passcode validation screen.||||||||
