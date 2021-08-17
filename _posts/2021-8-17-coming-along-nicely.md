---
layout: post
tag: journal, rust, gamedev 
title: Journal-1 Coming along nicely?
author: River
---



<figure class="figure">
  <img src="/assets/images/pictures/2.jpg" class="figure-img img-fluid rounded" alt="night">
  <figcaption class="figure-caption text-center">Unknown position</figcaption>
</figure>

I'm not dead yet, just a quick update.

The job it's going well so far. I've been busy doing adult stuff and giving myself some time i needed. It's quite complicate to balance your personal life, job, hobbies and friends. 

I've been keeping with learning Rust. I'm just going slower with it. I really like the language but it's tricky. Specially all the tings related to borrowing and how the language manages memory on reference types. Although, the thing that I have been struggling the most it's code organization. I'm still waiting the get the grasp of it, how to use modules and structure the project in different files. I come from a background heavy on OOP and Java, which organizes code via hierarchies, classes and packages. Rust it's quite different in that regard, but I like it. Sooner or later I will understand. With patience.

This block of code won't compile in Rust. At first glance it should. But It won't because how Rust manages memory. See, the owner of the reference type s it's the main function. When main calls the get_len() function and passes around the s variable it's also transferring the ownership of that variable to the get_len() function. Unless get_len() returns the value, cannot use s anymore. That's one of the may quirks of Rust. For now I like it enough.

```rust
fn main(){
	let s : String = String::from("test");
	get_len(s);
	println!("{}",s);
	
}

fn get_len(s : String) -> i32 {
	s.len()
}
```

On the other hand *Craptcha* the game I'm polishing in order to publish it's coming along nicely. But I'm the only programmer on it right now and it's a bit cumbersome. Specially because it has a lot of UI stuff an managing what is visible to the player and what not etc... I'm making progress but a bit every time. No screenshots for now, but soon, the game will be available to play.

Also, I have created a new twitter account. Later I will update the link a the top of the page.

Take care.
