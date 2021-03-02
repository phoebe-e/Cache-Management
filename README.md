# Cache-Management

## First In First Out (FIFO)

The FIFO cache management technique will place any “miss” into the cache, up until the cache is full (the cache can only hold 8 pages).

When the cache is full, the page that has had the longest time since it was added is evicted.

## Least Frequently Used (LFU)

The LFU cache management technique will place any “miss” into the cache up until the cache is full (the cache can only hold 8 pages).

Each “hit” against a cached page is logged and used in deciding which page to evict.

When the cache is full, the page that has the fewest “hits” is evicted from the cache. In case of two pages having the same amount of hits, the lowest numbered page should be evicted.


