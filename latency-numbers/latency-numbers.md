| Operation                                    |                           Time in 1 ns                           |                               Time in ms (1 ms=1,000,000 ns) |
|----------------------------------------------|:----------------------------------------------------------------:|-------------------------------------------------------------:|
| `L1 Cache Reference`                         |     <span style="font-size: 22px; color: #1a9850;">1</span>      |                                                              |
| `Branch Mispredict`                          |     <span style="font-size: 16px; color: #66bd63;">3</span>      |                                                              |
| `L2 Cache Reference`                         |     <span style="font-size: 14px; color: #a6d96a;">4</span>      |                                                              |
| `Mutex Lock/Unlock`                          |     <span style="font-size: 12px; color: #d9ef8b;">17</span>     |                                                              |
| `Main memory reference`                      |    <span style="font-size: 10px; color: #ffffbf;">100</span>     |                                                              |
| `Compress 1 KB with zippy`                   |    <span style="font-size: 8px; color: #fee08b;">2,000</span>    |  <span style="font-size: 11px; color: #d73027;">0.002</span> |
| `Read 1 MB sequentially from memory`         |   <span style="font-size: 10px; color: #e0b48e;">10,000</span>   |  <span style="font-size: 12px; color: #f46d43;">0.012</span> |
| `Send 2 KB over 10 Gbps network`             |   <span style="font-size: 12px; color: #d95f0e;">1,600</span>    | <span style="font-size: 12px; color: #a50026;">0.0016</span> |
| `SSD 4kb random read`                        |   <span style="font-size: 14px; color: #993404;">20,000</span>   |  <span style="font-size: 14px; color: #662506;">0.020</span> |
| `Read 1MB sequentially from SSD`             | <span style="font-size: 16px; color: #662506;">1,000,000</span>  |      <span style="font-size: 16px; color: #993404;">1</span> |
| `Round trip within same datacenter`          |  <span style="font-size: 18px; color: #a63603;">5,00,000</span>  |    <span style="font-size: 18px; color: #e6550d;">0.5</span> |
| `Read 1 MB sequentially from disk`           | <span style="font-size: 20px; color: #d94801;">5,000,000</span>  |      <span style="font-size: 20px; color: #fd8d3c;">5</span> |
| `Read 1 MB sequentially from 1 Gbps network` | <span style="font-size: 22px; color: #f16913;">10,000,000</span> |     <span style="font-size: 22px; color: #fd8d3c;">10</span> |
| `Disk seek`                                  | <span style="font-size: 24px; color: #f16913;">10,000,000</span> |     <span style="font-size: 24px; color: #fd8d3c;">10</span> |
| `TCP packet round trip between continents`   | <span style="font-size: 26px; color: #f16913;">10,000,000</span> |    <span style="font-size: 26px; color: #fd8d3c;">150</span> |

Source:
1. [About the author](https://research.google/people/jeff/)
2. [Google user content pdf](https://static.googleusercontent.com/media/sre.google/en//static/pdf/rule-of-thumb-latency-numbers-letter.pdf)
