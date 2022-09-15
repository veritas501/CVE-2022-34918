# CVE-2022-34918 LPE POC

尝试结合了一下360提出的[USMA](https://vul.360.net/archives/391)利用思路，还不错。

Chinese writeup: 
- [CVE-2022-34918 netfilter 分析笔记](https://veritas501.github.io/2022_08_02-CVE-2022-34918%20netfilter%20%E5%88%86%E6%9E%90%E7%AC%94%E8%AE%B0/)
- [基于USMA的内核通用EXP编写思路在 CVE-2022-34918 上的实践](https://veritas501.github.io/2022_08_11_%E5%9F%BA%E4%BA%8EUSMA%E7%9A%84%E5%86%85%E6%A0%B8%E9%80%9A%E7%94%A8EXP%E7%BC%96%E5%86%99%E6%80%9D%E8%B7%AF%E5%9C%A8%20CVE-2022-34918%20%E4%B8%8A%E7%9A%84%E5%AE%9E%E8%B7%B5/)

!! **For educational / research purposes only. Use at your own risk.** !!

(poc below in under poc_keyring_normal folder)
![](assets/lpe.png)

## 参考

- https://github.com/randorisec/CVE-2022-34918-LPE-PoC

- https://randorisec.fr/crack-linux-firewall/

- https://starlabs.sg/blog/2022/06-io_uring-new-code-new-bugs-and-a-new-exploit-technique/

- https://vul.360.net/archives/391
