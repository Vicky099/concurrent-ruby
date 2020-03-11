# TEMPORARY REPO !!!

This is temporary for of
<https://github.com/ruby-concurrency/concurrent-ruby> in order to fix
<https://github.com/ruby-concurrency/concurrent-ruby/issues/808>

> NOTE - this is already fixed! do `bundle update concurrent-ruby` so this repo is not needed

```
Finished in 49.25 seconds (files took 9.17 seconds to load)
25 examples, 0 failures

[BUG] Segmentation fault at 0x0000000000000050
ruby 2.6.3p62 (2019-04-16 revision 67580) [x86_64-linux]

-- Control frame information -----------------------------------------------
c:0001 p:---- s:0003 e:000002 (none) [FINISH]


-- Machine register context ------------------------------------------------
RIP: 0x00007f531acb47c3 RBP: 0x00007f5307576e50 RSP: 0x00007f5307576c90
RAX: 0x0000000000000000 RBX: 0x00007f531acb4a70 RCX: 0x000055d53b7b2030
RDX: 0x000055d53b7b1c18 RDI: 0x000055d5463a4848 RSI: 0x000055d5463a45f0
R8: 0x0000000000000000  R9: 0x000055d547ff6ac9 R10: 0x000055d547ff6ab0
R11: 0x00007f531b0106b0 R12: 0x000055d5463a45f0 R13: 0x00007f5307577700
R14: 0x00007f531b002a90 R15: 0x00007f5307576ea8 EFL: 0x0000000000010297

-- C level backtrace information -------------------------------------------
corrupted double-linked list
Aborted (core dumped)
```

I'll remove this fork repo once new version of concurrent-ruby gem is released

