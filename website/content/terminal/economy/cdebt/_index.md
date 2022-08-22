```
usage: cdebt [-h] [--export EXPORT] [-l LIMIT]
```
National debt statistics for various countries. [Source: Wikipedia]

```
optional arguments:
  -h, --help            show this help message (default: False)
  --export EXPORT       Export raw data into csv, json, xlsx (default: )
  -l LIMIT, --limit LIMIT
                        Number of entries to show in data. (default: 20)

For more information and examples, use 'about cdebt' to access the related guide.
```

Sample usage:

```
2022 Aug 12, 16:51 (🦋) /economy/ $ cdebt

                    National Debt (USD)
┏━━━━┳━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━┓
┃    ┃ Country        ┃ Debt                 ┃ Per Capita ┃
┡━━━━╇━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━┩
│ 1  │ United States  │ 30,400,000,000,000.0 │ 60,526.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 2  │ China          │ 13,000,000,000,000.0 │ 8,248.0    │
├────┼────────────────┼──────────────────────┼────────────┤
│ 3  │ United Kingdom │ 9,020,000,000,000.0  │ 127,000.0  │
├────┼────────────────┼──────────────────────┼────────────┤
│ 4  │ France         │ 7,320,000,000,000.0  │ 87,200.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 5  │ Germany        │ 5,740,000,000,000.0  │ 69,000.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 6  │ Japan          │ 4,770,000,000,000.0  │ 38,000.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 7  │ Italy          │ 2,510,000,000,000.0  │ 42,300.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 8  │ Spain          │ 2,260,000,000,000.0  │ 48,700.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 9  │ Canada         │ 1,930,000,000,000.0  │ 52,300.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 10 │ Australia      │ 1,830,000,000,000.0  │ 71,906.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 11 │ Switzerland    │ 1,820,000,000,000.0  │ 213,100.0  │
├────┼────────────────┼──────────────────────┼────────────┤
│ 12 │ Singapore      │ 1,670,000,000,000.0  │ 231,000.0  │
├────┼────────────────┼──────────────────────┼────────────┤
│ 13 │ Belgium        │ 1,280,000,000,000.0  │ 112,000.0  │
├────┼────────────────┼──────────────────────┼────────────┤
│ 14 │ Sweden         │ 994,000,000,000.0    │ 94,500.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 15 │ Austria        │ 757,000,000,000.0    │ 84,061.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 16 │ Norway         │ 604,000,000,000.0    │ 117,000.0  │
├────┼────────────────┼──────────────────────┼────────────┤
│ 17 │ India          │ 614,900,000,000.0    │ 6,390.0    │
├────┼────────────────┼──────────────────────┼────────────┤
│ 18 │ Brazil         │ 556,000,000,000.0    │ 3,200.0    │
├────┼────────────────┼──────────────────────┼────────────┤
│ 19 │ Netherlands    │ 555,000,000,000.0    │ 26,540.0   │
├────┼────────────────┼──────────────────────┼────────────┤
│ 20 │ Russia         │ 489,000,000,000.0    │ 3,700.0    │
└────┴────────────────┴──────────────────────┴────────────┘
```