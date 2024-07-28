---
authors: ["Osama Dabbousi"]
title: Chess Anti-Cheat Detection Using an Adversarial Network Framework
paper_url: /static_files/projects/dabbousi_chess_anti_cheat.pdf
video_url: "https://mymedia.bu.edu/media/t/1_1ngipkqi"
slides_url: /static_files/projects/dabbousi_preso.pdf
tags: ["GAN", "RL"]
---

The creation of powerful chess programs in past years has made cheating in the
game easy and prevalent. This fact has facilitated a need for high quality chess anticheats capable of detecting AI play. While such algorithms exist, they often focus
on better-than-human play as opposed to non-human play. To address this issue, in
this paper we introduce ChessGAN. ChessGAN is a generative adversarial network
whose generator learns to play human-like chess, while its discriminator is trained to
distinguish human moves from AI moves. We find that while such a discriminator was
capable of distinguishing its generator, this training did not generalize to all human or
AI play. However, we did find that the use of this discriminator aided in the training of
a generator which played high-quality chess with a move distribution closely resembling
that of human players.
