NASM, the Netwide Assembler
===========================

[![master](https://travis-ci.org/netwide-assembler/nasm.svg?branch=master)](https://travis-ci.org/netwide-assembler/nasm)

Many many developers all over the net respect NASM for what it is:
a widespread (thus netwide), portable (thus netwide!), very flexible
and mature assembler tool with support for many output formats (thus netwide!!).

Now we have good news for you: NASM is licensed under the "simplified"
[(2-clause) BSD license](https://opensource.org/licenses/BSD-2-Clause).
This means its development is open to even wider society of programmers
wishing to improve their lovely assembler.

Visit our [nasm.us](https://www.nasm.us/) website for more details.

With best regards, the NASM crew.


Hi! I am working on using nasm in open-source service mesh community Envoy(https://github.com/envoyproxy/envoy).

And I have raised a PR to integrate nasm to envoy, see this(https://github.com/envoyproxy/envoy/pull/22651). 

And envoy uses OSSF scorecard(https://blog.envoyproxy.io/security-scorecards-envoy-automating-supply-chain-analysis-7b8fd9829169) to test open source github repo to see how it would behave as an envoy dependency. 

But the result score of nasm is a bit low, like this(https://github.com/envoyproxy/envoy/pull/22651#discussion_r948011839).

However, many of the issues could be easily improved in nasm github repo.
For example, adding a security policy is easy and important, also setting branch protection should just be a github-level thing.

Could you help fix some very simple issues to improve nasm's security score of ossf scorecard? Thanks! 


