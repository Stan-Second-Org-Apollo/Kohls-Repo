# Account Link Failed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Account Link Failed",
    "sephoraEmailNotFound": "<sephoraEmailNotFound>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|sephoraEmailNotFound|boolean|Customer lands on the enrollment form for Sephora Beauty Insider, after attempting to link their Kohls account to a Beauty Insider account but no matching email was found in the Beauty Insider system.||||||||
