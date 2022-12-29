# Gene of the Day Bot

A Mastodon bot that tweets the official* gene of the day. Currently live on [Mastodon](https://botsin.space/@gene_of_the_day)!

This bot runs every morning on a raspberry pi via a cron job:

```
0 8 * * * cd ~/Documents/gene_bot/src && /usr/bin/python3 ~/Documents/gene_bot/src/build_bot.py
```

*_According to numpy's random number generator._

## Example post:

<img src='img/example_post.png' height="600">

### Data versions:
PDB data current as of: Dec 28, 2022\
Uniprot data current as of: Aug 2, 2022\
Pubtator data current as of: Nov 11, 2021\
NCBI Gene data current as of: Aug 16, 2022
