---
title: "My Entirely Subjective Take on PoP!_OS"
path: "/pop!_os"
date: "2019-03-24"
coverImage: "../images/pop-os.png"
author: "Ryan"
excerpt: "Recently I changed careers and was lucky enough to be hired by an amazing software development company in Sydney called Alembic.  Prior to this, my career ..."
tags: ["linux", "debian", "arch", "system76"]
---

Recently I changed careers and was lucky enough to be hired by an amazing software development company in Sydney called Alembic. Prior to this, my career was in Environmental Conservation though I have always been into tech. Ever since my parents brought home our very first desktop computer with the Tabworks Windows 3.1 shell on it. It was a boxy Compaq "Portable" 486 Presario that had the monitor and tower build into each other.

<div style="width:15em;font-size:808;text-align:center;margin:10px;float:right">
<img src="https://i.pinimg.com/originals/05/07/9f/05079ff28c8abc9b25d13002774531b1.jpg" style="width:15em;">
<em>Sexy, right?</em>
</div>

These days I am rocking a Lenovo T440s. I've been running Arch on this beauty since I bought it four years ago second hand for \$400. It has never missed a beat, and besides the horrid track-pad has been damn near a perfect machine for me.

I love it. I hope to continue to love it for many years to come. However, due to my new position as a Junior Dev, I felt like I needed more power. The T440s also doesn't have an HDMI port, and it has caused me trouble on a number of occasions when I have had to give presentations. The screen is not great either, and I am finding myself wanting the real estate of a 15 inch laptop.

Plus, I love new toys. And with the rest of the dev team all using the latest MacBook Pro's, I had to represent. So, I decided to get a fully spec'd Lenovo X1 Extreme.

The thing arrives next week, and before I get it, I wanted to ensure that I would be able to have a linux distro on it that would be stable enough to not potentially run into problems along the way. I've been an Arch user, purely, for 7 years now. And not because I'm some kind of tech genius. Far from it, infact I bet I reach for Google just as much if not more than the next Linux user. The reason I use Arch is because of it's modular, start from the ground up philosophy. With this approach, I have the ability to create an operating system that is a direct reflection of what I want, how I work and what I feel is important, with out anything extra. It allows me to create a more accurate digital imprint of my personality so my OS feels more like me. Philosophical perhaps, but something that I find value in.

But now, my operating system was not just going to be for my own personal needs. The new laptop was going to be for business. I needed this thing to be stable. Don't get me wrong, Arch is stable, and it's reputation for instablity is a gross misrepresentation (these days anyway). But there have been times when I have had to do a bit of debugging to get things working just the way I want them to. And while I get alot of joy out of doing that, I can not justify having to do that when it comes to my professional life. Plus now that I am working on computers 9-5, I find myself not wanting to spend so much time behind the scenes. So, I turned to everyone's old friend.

Ubuntu.

And I quickly turned away again. I just couldn't. I could feel the bloat through the screen of my Google search. Maybe Manjaro would be a valid option. Even with the bloat of Manjaro I would still be under the umbrella of Arch. I found it difficult to even move slightly away from Arch. Apt vs Pacman, PPA's vs the AUR, these things kept looping through my mind, keeping me awake at night. Arch spoils you as a user. It gives you every freedom, and the thought of having that freedom taken away from me was a sad reality that I didn't want to face.

But I am full of shit. And if you know what you are doing, you can easily have as much flexibilty outside of Arch if you do a bit of digging. And that's how I found PoP!\_OS.

I'm not going to give the speil, there's loads of information about Pop!\_OS by people who know the lingo much better than I.

Like this guy.

`youtube: sbiQcGU0hHc`

Pop!\_OS is a minimal Ubuntu based distro. And I mean actually minimal, it comes with Geary instead of Thunderbird, that says it all. It does come with LibreOffice already installed but that's all good, I would have to install it anyway.

System76 claims that this OS is for devs, scientists and creative types. I'm not sure exactly what that means because there were no packages installed that would appeal to any of those categories and I still had to go through the rigor of setting up my dev environs. Be nice if they had a postgres installer atleast. That would help me a ton.

PoP!\_OS is designed using Gnome keyboard oriented navigation in mind. I love keyboard navigation and it's how I get around, so the simplicity of Gnome has always appealed to me. But anyone who is a keyboard navigator will have their own keyboard shortcuts ingrained in the souls of their fingers. The fact that System76 has spent a bit of time creating a decent default keyboard map is great, and shows that they are trying to push linux in a great direction. But anyone who is a keyboard navigator is going to change their defaults. It's usually the first thing I do. And it was the first thing I did.

Also I never understand why Gnome don't just add a workspace grid option into their packages. They used to, what happened? Again, installing Workspace Grid is one of the first things I do when I install a new distro.

There are things however, that PoP!\_OS comes out of the box with that made me giddy with delight. Yes having NVIDIA GPU working like a charm straight up is amazing, and is one of the things that appealed to me, having the X1 Extreme in the mail. Even if you do need to choose the GPU and then restart the machine. That's a thing I am willing to do for stability. Besides, the X1 Extreme's battery life is the worst, I'm not going to be saving that much battery time by changing GPUs repeatedly

But you know what really made me smile? PoP!\_OS automatically connects your Google Drive account to your files explorer so it's just like another folder you can interact with.

I HAVE NEVER THOUGHT ABOUT DOING THAT!

So when you want to drop a folder into Google Drive, you just drag it and drop it right in there like you would anything else.

Maybe Ubuntu does this already, I wouldn't know.  Maybe all the things I love about Pop!_OS are actually Ubuntu things.

That scares me.

Also, it comes with a blue light filter pre-installed which for me is a god-send because I often have difficulty getting Redshift or Flux stable enough to be helpful.

The PoP!\_OS theming is really nice. It is a flat-style approach with some really awesome colour scheming which works incredibly well with the Gnome OS aesthetic. You can tell quite a bit of time was spent on how the distro looks, and I really appreciate the effort.

<div style="width:15em;font-size:808;text-align:center;margin:10px;float:right">
<img src="../images/archlinux.png" style="width:15em;">
<em>The Teacher</em>
</div>

Getting everything up to my usual linux standards didn't take long at all. Everything installed easily, no conflicts, minimal config file digging. And you know what? The place is starting to feel like my own. Besides ArcoLinux, I have never experienced this outside of a base Arch install. even Antergos got in the damn way. PoP!\_OS does an amazing job of getting out of the way of how you want your distro to be. I love the feel of it too. Probably more than when I get all "UX designer" with my OS.

Am I staying?

As much as I love Arch linux, I do not see a valid enough reason to go back. I will miss the freedom of using yay with the AUR. I will miss the simple beauty of Arch's package manager. I will miss the feeling of pride I have when I say that I am an ArchLinux user. But PoP!\_OS is polished enough and has enough freedom to be what I need it to be. I am not an advanced power user, I am more of a mid-weight power user, and PoP!\_OS fills my needs completely. The extra peace of mind and support of Debian coupled with my mediocre linux know-how from years inside Arch, is enough to make an Ubuntu based distro a good idea.

In saying that, I don't think I would have the same feeling if I had not been trained under the fire of ArchLinux. Because of Arch, I know where things are, I know how Linux works, so when Ubuntu shows me their wall, I know where the gate is. Because of Arch, I have learnt to appreciate the power of what Linux is. And due to that understanding, it has allowed me to find that appreciation in all distros.

<div style="width:7em;font-size:808;text-align:center;margin:10px;float:left">
<img src="../images/sadtux.png" style="width:7em;">
<em></em>
</div>

And I have to say that I am really keen to see what System76 have planned for the world of Linux, and am excited to be a part of the movement.

And so it is with a little sadness that I say farewell to ArchLinux.

For now.
