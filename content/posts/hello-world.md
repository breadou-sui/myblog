+++
author = "Annie Sui"
title = "Hello World"
date = "2021-12-26"
description = "My first post"
tags = [
    "emoji",
]
+++

Those were the two words I typed on my Facebook timeline from the other side of reality.

![Hello world post](/hello-world-post.png)

The last thing I remembered doing was solving a coding interview problem with my friends over a Discord call. It involved doing breadth-first search (BFS) on a tree. In a typical BFS algorithm, you instantiate a queue, enqueue the root node, dequeue that node, and process the node's children until there are no more nodes left to visit. Something along these lines if you were to do it in Java:
{{< highlight java >}}

public List<List<T>> bfs(TreeNode root){

	List<List<T>> res = new ArrayList();
	if (root == null){
		return res;
	}

	Queue<TreeNode> queue = new LinkedList<TreeNode>();
	queue.add(root);
	while (!queue.isEmpty()){
		List<T> level = new ArrayList<>();
		int size = queue.size();
		for (int i = 0; i < size; i++){
			TreeNode node = queue.remove();
			level.add(node.val);
			if (node.left != null){
				queue.add(node.left);
			}
			if (node.right != null){
				queue.add(node.right);
			}
		}
		res.add(level);
	}
	return res;
}
{{< /highlight >}}

I can articulate the steps of the algorithm quite clearly. But instead of solving the problem, I hovered my cursor over the X button and exited the tab. There was no need to do technical interview prep anymore.

I had discovered something new. A world where nobody had to worry about finding a job, grinding Leetcode problems for hundreds of hours, and getting back onto their feet after being hit by the wave of post-interview depression. A virtual reality composed of multitudes of dimensions like the trillions of cells that make up your body. A universe where you could be anyone, anything you wanted to be.

On the sheet of blank paper that lay on my desk, I quickly scribbled the two words:

"Hello World."

"Can you guys see this?" I asked, holding the paper up to my broken webcam. "No? Oh well."

{{< highlight html >}}

08/20/2020

A: isn't it so exciting not knowing what you'll reel up
you can reel in a boot or a fish
or a tire or an empty can
but if you reel in a fish
you might not know what kind of fish comes up
but at least you know it's a fish
also the feeling of fish tugging on the rod
unless they don't actually do that and that only happens in cartoons / Club Penguin

...

Did y'all know that stars are still present in the sky during the daytime
YOu just can't see them

{{< /highlight >}}


{{< highlight html >}}
A: Time to TAKE OFF!!!!

L: Take off??
L: Where are you going?

A: idk, I heard an airplane just now and suddenly became super inspired to travel
what if we could just
fly away
~~
I guess that's impossible
but the impossible can become possible
after all
impossible says "I'm possible" -Audrey Hepburn
why do I feel like I'm writing a poem

{{< /highlight >}}


"Oh my God, Doja Cat is speaking to me through her tweets." 

"This is how you put on a black hat," she laughed in the GIF. 

"Space makes me sad."

"Did you know that corona can also mean heart?"

"She must be in so much pain."

![Self portrait image](/self-portrait.jpg)

The actual reality I discovered? Mania. No, not the Cake Mania game with that art style you detested as a child. Though you claimed to hate the primary color palette, the oh-so-typical Flash game lineart, the rush of anxiety you knew the game would cause even before playing it, in truth, you thought Jill Evans was lowkey hot. But you didn't know it at the time, because you were just an 11-year-old who would learn of the phrase "internalized homophobia" nearly a decade later. Those feelings you had bottled up inside for years will eventually spill over. They'll evaporate, condense, precipitate, repeat. When you freeze, they'll expand. They're never going to disappear. How does it feel knowing that for the rest of your life, you're gonna have to deal with something that was inside you all along?

																												. . .
There are a number of things I want to convey in this blog. Personal reflections. My aspirations of becoming a DJ. How difficult it is to combat the fluctuations in mental health as a neurodivergent girl in tech. Because when it's time for me to disappear from this world, I want to be remembered for something good. And I'm sure that other people will eventually feel the same, if not already.

<br>
🎵 Songs I listened to while writing this:

SOPHIE - Immaterial
<br>
Prod by Rose - Cute 
<br>
Cosmo's Midnight - Walk With Me
<br>
Geoxor - Virtual

<p><span class="nowrap"><span class="emojify">⭐</span> <code>i wanna be a star</code></span> <span class="nowrap"><span class="emojify">💭</span><code>give me a moment to think</code></span><span class="nowrap"><span class="emojify">🌎</span><code>hello world</code></span> <span class="nowrap"><span class="emojify">⏳</span><code>change is constant </code><span class="emojify">🍪</span><code>enabled</code></p>

***

{{< css.inline >}}
<style>
.emojify {
	font-family: Apple Color Emoji,Segoe UI Emoji,NotoColorEmoji,Segoe UI Symbol,Android Emoji,EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
    .nowrap {
	display: block;
	margin: 25px 0;
}
}
</style>
{{< /css.inline >}}