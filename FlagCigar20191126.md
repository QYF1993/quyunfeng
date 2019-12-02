Bioinformatic homework

Explain BAM FLAG value： 143 
template having multiple segments in sequencing each segment properly aligned according to the aligner segment unmapped next segment in the template unmapped the last segment in the template
Explain BAM FLAG value： 99 
template having multiple segments in sequencing each segment properly aligned according to the aligner SEQ of the next segment in the template being reversed the first segment in the template
Explain BAM FLAG value：516 
segment unmapped not passing quality controls
Explain BAM FLAG value： 2064 
SEQ being reverse complemented supplementary alignment
Explain BAM FLAG value： 147 
template having multiple segments in sequencing each segment properly aligned according to the aligner SEQ being reverse complemented the last segment in the template
Explain BAM CIGAR：14M2D31M 14个match，2个缺失（查询序列没有但参考序列有），31个match(match可能是正确匹配的，也可能是错配)
Explain BAM CIGAR：3S6M1D5M 开始的3个字符不考率，6个match，1个缺失，5个match
Explain BAM CIGAR: 6M14N5M 6个match，14个插入（查询序列有但是参考序列没有），5个match的
Explain BAM CIGAR: 7M5D8M2I14M (小写：7m5d8m2i14m） 7个match，5个缺失，8个match，2个插入，14个match
how long is the read with alignment CIGAR of 7M5D8M2I14M? 7+8+2+14=31bp
