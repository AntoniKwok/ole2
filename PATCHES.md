# Fork of extrame/ole2 with fixes

Based on `github.com/extrame/ole2` master (d694296) plus: no `log.Fatal` on corrupt files,
cyclic or out-of-table sector chains return `ErrCorruptChain`, reads stop at the stream's declared
size, DIFAT cycles are rejected.

Upstream PR: extrame/ole2#6.
