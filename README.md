# Maximum-Subarray-Sum

This finds the maximum subarray sum modulo m using prefix sums. It tracks cumulative sums and stores them in a sorted set. For each new prefix, it checks if any previous prefix is slightly larger - this creates the maximum possible modulo difference. The maximum result is either a prefix sum itself or the difference between current and a larger previous prefix. This efficiently finds the optimal subarray without checking all possibilities.
