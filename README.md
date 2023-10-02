# hivemapper-mga-tool

This tool download MGA offline data from u-blox offline data web service and compute is hash.

## Usage

Download the latest version of the tool from the [releases page](https://github.com/streamingfast/hivemapper-mga-tool/releases) and un-compress it.

```bash
/path-to-binary/mga download "https://offline-live1.services.u-blox.com/GetOfflineData.ashx?token=YOUR_TOKEN_HERE;gnss=gps"
```

## Warning

Be careful! Once repo is not touched for 2 months+,
github stops executing the scheduled Actions in it, that can prevent us from updating the MGA file for production.
TBD

