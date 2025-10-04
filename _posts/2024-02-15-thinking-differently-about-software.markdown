---
layout: post
title:  "Thinking differently about software"
date:   2024-02-15
---
I write JavaScript everyday. JavaScript is great. The ecosystem... not so much. Some of the new meta frameworks like [Astro](https://astro.build) and [Sveltekit](https://svelte.dev) are promising and hit the right marks.

Nevertheless, every website I work on from the simplest to the most complex needs a server. They need a database. They need authentication. They need authorization. The list goes on and on but nevertheless I keep coming back to full stack frameworks like [Rails](https://rubyonrails.org), [Django](https://www.djangoproject.com), and I really like where [Adonis.js](https://adonisjs.com) is going.

That said, Rails... Rails is so good in 2024. Most people do not appreciate how fast Ruby 3.3.0 is. They do not appreciate how great using Rails with Sqlite is for 99.99% of use cases. Mostly, they do not understand how incredible [Kamal](https://kamal-deploy.org) is. Kamal is an absolute game changer. It finishes the circle of developer happiness by making deployment to a server I own a cinch.

That last piece is crucial: ownership. If I build a Rails app in 2024, not only can I do high fidelity frontend work with [Hotwire](https://hotwired.dev) and [Stimulus.js](https://stimulus.hotwired.dev) but I can own the stack back to front and handle devops on a real server for almost every conceivable use case.

Finally, I want to talk about software and dependencies. Everything you write has dependencies. They are not evil per se but, in my opinion, they should be aggressively limited. Think about using something like [Nextjs](https://nextjs.org). You are on the hook for maintaining the following, at least, as time goes on:

1. React updates with breaking changes
2. Nextjs updates with breaking changes
3. Tailwindcss updates with breaking changes
4. Typescript updates with breaking changes
5. Vercel updates with breaking changes

On a large app these dependencies will not be trivial to keep up-to-date. Sticking with vanilla Rails, vanilla CSS, and sprinkles of JS with Stimulus means reduced misery when you have to keep your app up-to-date in the years to come.

I think Astro, Sveltekit, and some of the others will eventually get closer but they aren't there yet; not even close.

Well done Rails, well done.

