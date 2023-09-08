This script control mouse and keyboard that work with browser to download option chain in csv format from CBOE.

It is limited by the computer screen size and etc. In the other words, if you use another computer, you need to adjust mouse locations.

```bash
#cygwin
sleep 1; for i in `echo NVDA TSLA META` ; do echo $i;  mkinput csvd.yml $i ; done
```
