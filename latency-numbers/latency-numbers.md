| Operation  | Time in 1 ns | Time in ms (1 ms=1,000,000 ns) |
| ------------- | ------------- | ------------- |
| `L1 Cache Reference` | 1  |    |
| `Branch Mispredict`  | 3  |    |
| `L2 Cache Reference`  | 4  |    |
| `Mutex Lock/Unlock`  | 17  |    |
| `Main memory reference`  | 100  |    |
| `Compress 1 KB with zippy`  | 2,000  |  0.002  |
| `Read 1 MB sequentially from memory`  | 10,000  |  0.012  |
| `Send 2 KB over 10 Gbps network`  | 1,600  |  0.0016  |
| `SSD 4kb random read`  | 20,000  |  0.020  |
| `Read 1MB sequentially from SSD`  | 1,000,000  |  1  |
| `Round trip within same datacenter`  | 5,00,000  |  0.5  |
| `Read 1 MB sequentially from disk`  | 5,000,000  |  5  |
| `Read 1 MB sequentially from 1 Gbps network`  | 10,000,000  |  10  |
| `Disk seek`  | 10,000,000  |  10  |
| `TCP packet round trip between continents`  | 150,000,000  |  150  |

Source:
1. [About the author](https://research.google/people/jeff/)
2. [Google user content pdf](https://static.googleusercontent.com/media/sre.google/en//static/pdf/rule-of-thumb-latency-numbers-letter.pdf)
