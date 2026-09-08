# Interview Questions
**Company:** JPMorgan Chase
**Profile:** Data and AI

**Result:** Accepted.

**Round 1**
- Trapping Rain Water (LeetCode).
- DP problem: n people have to paint their house with either red, blue or green
  and the respective cost matrix was given. The interviewer just wanted the DP
  equation once I said we can use DP, and moved on.
- Stack based problem: given an array, output an array whose elements are the
  next greater element from the input array, else -1.
  - Input `[3,1,4,2,9]` -> Output `[4, 4, 9, 9, -1]`
  - Input `[9, 4, 5, 1, 3]` -> Output `[-1, 5, -1, 3, -1]`
- One probability question - too easy to remember; something solvable with an
  infinite GP.
- Transformer architecture, since it was in my project: how self-attention and
  cross-attention differ, the flow of query, key and value matrices from encoder
  and decoder. Make sure you are very clear on all projects you have done and are
  thorough with architecture - as you can see they are ready to go to this depth.
- How do RNNs and LSTMs pale in comparison? I had to explain how the transformer
  architecture is parallelisable, how we could use KV caching to reduce the
  quadratic complexity of computing attention, etc.

**Round 2** - Complete resume grilling.
- Since Viveka never really had a well defined conclusion or proper results, I was
  questioned mercilessly about the point of those endeavours. I answered that
  taking on such open problems felt challenging, and while we may have failed to
  get reasonable conclusions, so have many other people in the field as this is
  still an open research problem. I also mentioned that the growth was huge in
  understanding the internal architecture in depth and in coming up with
  experiments to detect hallucinations.
- Asked about other projects on my resume. The interviewer was fascinated with one
  project related to CPU and GPU fuzzing and mentioned that even companies are now
  starting to do this.
- He also humoured me and asked things like how would you differentiate between AI
  and ML. At first I was not sure what he was expecting, but with more knowledge
  dumps I figured out what he wanted.

**Round 3** - HR round.
