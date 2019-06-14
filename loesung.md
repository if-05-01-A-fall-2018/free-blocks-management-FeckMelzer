#### a) 
*Taking 5 Blocks from Block 17*

| Block # | 17  | 18 | 
|---|---|---|
|  Next Block | 18  | 0  |
|   | 4589  |  24353 |
|   | 43546  |  98745 |
|   | 718  |  76345 |
|  | 345   |  9877 |
|   |   |  7345 |
|   |   |  34535 |
|   |   |  154698 |
|   |   |  967 |
|   |   |  8657 |

#### b)
*Block 22 is marked as free in block 17*

| Block # | 17  | 18 | 
|---|---|---|
|  Next Block | 18  | 0  |
|   | 4589  |  24353 |
|   | 43546  |  98745 |
|   | 718  |  76345 |
|  | 345   |  9877 |
|   | 22  |  7345 |
|   |   |  34535 |
|   |   |  154698 |
|   |   |  967 |
|   |   |  8657 |

#### c)
*Taking 5 Blocks from Block 17*

| Block # | 17  | 18 | 
|---|---|---|
|  Next Block | 18  | 0  |
|   |   |  24353 |
|   |   |  98745 |
|   |   |  76345 |
|   |   |  9877 |
|   |   |  7345 |
|   |   |  34535 |
|   |   |  154698 |
|   |   |  967 |
|   |   |  8657 |

#### d)
*Taking another Block results in: No next Block in Block 17 and taking one Block from Block 18,
17 is marked as free block in 18*

| Block # | 17  | 18 | 
|---|---|---|
|  Next Block |   | 0  |
|   |   |  24353 |
|   |   |  98745 |
|   |   |  76345 |
|   |   |  9877 |
|   |   |  7345 |
|   |   |  34535 |
|   |   |  154698 |
|   |   |  967 |
|   |   | 17  |

#### e)
*Taking 3 Blocks from 18 wich means 17 is gone too, we have no information about Block 17 now*

| Block # |   | 18 | 
|---|---|---|
|  Next Block |   | 0  |
|   |   |  24353 |
|   |   |  98745 |
|   |   |  76345 |
|   |   |  9877 |
|   |   |  7345 |
|   |   |  34535 |
|   |   |   |
|   |   |   |
|   |   |   |

#### f)
*Four blocks are marked as free, but 18 can't hold 4 Blocks, Block 57 represents another Free-Management-Block now,
and references to Block 18*

| Block # | 56  | 18 | 
|---|---|---|
|  Next Block | 18  | 0  |
|   |   |  24353 |
|   |   |  98745 |
|   |   |  76345 |
|   |   |  9877 |
|   |   |  7345 |
|   |   |  34535 |
|   |   |  23456 |
|   |   |  8345345 |
|   |   |  634534 |
