# pi_data_view

## Deprecated 已废弃，请用 [bytes](https://crates.io/crates/bytes)代替

二进制数据的 视图结构

可以从 二进制对象中读写多种数值类型的底层接口,使用它时,不用考虑不同平台的字节序问题。

此外，额外提供一个名为 move_part 的 trait，可以将二进制的一个片段拷贝到改二进制的另一个位置
