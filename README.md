# API Endpoints and Configuration

## Configuration Variables

discordid=1169111190824308768

kirkaid=NUGGET

shortid=true

longid=false

## API Endpoints

### Kirka User Data

https://bot.kirka.io/api/data?userid={discordid}

### Get Profile (POST)

URL: https://www.smudgy.store/api/getprofile

<details>
<summary>Payload</summary>

```json
{
  "userId": "{kirkaid}",
  "isShortId": {shortid}
}
```

</details>

### Profile Image

https://www.smudgy.store/api/list/profile.png?meow={kirkaid}

### Google Sheets Data (Sorted View)

https://opensheet.elk.sh/1pxMSoaSo8FYv-OIJ26HpSj8EDy7EDRmatHyQW24o6E4/Sorted+View

### Trade History

https://www.smudgy.store/api/kirka/trade-history/dailyTrades.json

### Trade Snapshots

https://www.smudgy.store/api/kirka/trade-snapshots

### Api doc

https://api.kirka.io/api/docs/
