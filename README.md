# challenge-hyperloglog
HyperLogLog challenge for codecheck

#### Let's consider you have a list of 10 elements. Let these elements be IP addresses which are not necessarily unique.

**Step1.** Calculate the unique IP addresses.

**Step2.** Calcualte time and memory required to calculate unique IP addresses.

**Step3.** If the number of input changes from 10 to 1000 IP addresses calculate unique IP addresses and corresponding time and memory required.

**Step4.** Explain your code in [answer.md](answer.md)

**Step5.** Now consider the input changes from 1000 to 1 million IP addresses how will you calculate unique IP addresses ? Here you can calculate unique IP address approximately. Approximation error should not be more than 3%.

**Hint:**
  - [HyperLogLog](https://en.wikipedia.org/wiki/HyperLogLog)
  - http://algo.inria.fr/flajolet/Publications/FlFuGaMe07.pdf
  - https://stefanheule.com/papers/edbt13-hyperloglog.pdf

**Step6.** Explain your understanding of [HyperLogLog](https://en.wikipedia.org/wiki/HyperLogLog) in [answer.md](answer.md). Any inputs of how it can be improved are welcomed.

**Step7.** Give real world examples of where [HyperLogLog](https://en.wikipedia.org/wiki/HyperLogLog) can be used.
