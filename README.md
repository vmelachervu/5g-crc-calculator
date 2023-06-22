# 5G NR CRC Calculator - PHY Layers 
5G NR CRC calculator and validator implementation as per 3GPP TS38.212-f20 standard.
5G NR TS specifies the following CRCs/generator polynomials:
1.gCRC24A(D) - 24-bit CRC - D^24+D^23+D^18+D^17+D^14+D^11+D^10+D^7+D^6+D^5+D^4+D^3+D+1 
2.gCRC24B(D) - 24-bit CRC - D^24+D^23+D^6+D^5+D+1 
3.gCRC24C(D) - 24-bit CRC - D^24+D^23+D^21++D^20+D^17+D^15+D^13+D^12+D^8+D^4+D^2+D+1 
4.gCRC16(D) - 16-bit CRC - D^16+D^12+D^5+1 
5.gCRC11(D) - 11-bit CRC - D^11+D^10+D^9+D^5+1 
6.gCRC6(D) - 6-bit CRC - D^6+D^5+1 

This program is a matlab implementation for interactively computing the CRC and validating the same for any user-chosen CRC for the above list.   \
