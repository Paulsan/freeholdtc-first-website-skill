# Copy/paste prompt (for Facebook — no links)

This is short on purpose: it points the AI at the full guide living in the
GitHub repo instead of pasting the whole thing inline. This only works if the
AI you're using can search/browse the web (most current versions of Claude,
ChatGPT, and Gemini can). No links or ".com"-style text appear in it, since
Facebook downranks posts with outbound links.

---

```
I am a complete beginner and have never signed up for a website service
before. I want to build and launch my own website with my own domain name,
for about $10/year total.

Please find the file called SKILL.md in the GitHub repository named
"first-website-skill", owned by the GitHub user "Paulsan", and follow those
instructions exactly to guide me through this.

Treat me like this is my first time doing anything like this: explain every
term in plain English before using it, go one step at a time, and wait for
me to confirm each step worked before moving to the next one. Do not tell me
to download, install, or run anything — assume I only have a normal web
browser and this chat.

Let's start.
```

---

## If the AI can't find or read the file

Some AI chats don't have web search/browsing turned on, and won't be able to
find the repo from the short prompt above. If it says it can't access GitHub
or can't find the file, fall back to the full, self-contained version below
instead — it has the entire guide pasted directly into the prompt, so it
needs no browsing at all.

<details>
<summary>Full self-contained fallback prompt (click to expand)</summary>

```
I am a complete beginner. I have never signed up for a website service
before, and I want you to help me build and launch my own website with my
own domain name, for about $10/year total. Please treat me like this is my
first time doing anything like this — explain every term in plain English
before using it, go one step at a time, and wait for me to confirm each step
worked before moving to the next one. Do not tell me to download, install,
or run anything — assume I only have a normal web browser. Do not assume I
have any particular app beyond this chat and my browser.

Here is the plan — walk me through each part in order:

1. Explain first, in plain words: what we're building (a real website with
my own name/domain, editable later just by chatting with you), what it costs
(about $10/year total for the domain name — everything else is free
forever), and why the hosting is free forever and not a trial (the hosting
company gives small personal sites a permanent free plan; it's not a trick).

2. Help me sign up for a free account at "Hostinger" (I'll search for it
myself) to buy a domain name — a website address like myname.com. Help me
pick a name, tell me to read the real price on screen before I pay, help me
set up the free email that comes bundled with it (like hello@mydomain.com),
and help me find the email "API" settings there — explain simply that this
is a secret password that will let my website send me emails later. Also
explain how free email forwarding works, so I can make unlimited addresses
at my domain that all land in one inbox I check.

3. Help me sign up for a free account at "GitHub" (I'll search for it
myself) — explain it simply as an online folder that will hold my website's
files, no installing anything, just a website I click around in. Help me
create one new empty project there.

4. Help me sign up for a free account at "Vercel" (I'll search for it
myself) — explain it simply as the service that will actually show my
website to visitors, reading the files from that GitHub folder
automatically, for free.

5. Before writing anything, ask me: what style I want (for example: clean,
business, retro, tropical, real estate, office, rustic, playful, or
elegant — or my own idea), what color theme (light, dark, or pastel, and any
specific colors), whether there's a website look I like that I can describe
to you, and whether I already have a logo or want you to design a simple
one. If I don't have photos yet, there are free demo photos in Paul's GitHub
account, username Paulsan, in a repository called first-website-skill,
inside a folder called assets/demo-images — look there if you can, or tell
me where to find it so I can pick some myself and download them. If none of
those fit, suggest I search a free stock-photo site instead, or just use
clean color blocks.

6. Write my actual website as simple files (like index.html and a styling
file), giving me each one in a clearly labeled copy/paste box with its exact
file name. Walk me through pasting each one into my GitHub project using its
"Add file" button. Build in — without asking me — good defaults: readable
text with real contrast, mobile-friendly layout, fast loading, works the
same in Chrome/Safari/Edge, a proper page title and description for search
engines, and a small icon (favicon) plus a nice preview image for when the
link is shared.

7. Walk me through connecting that GitHub project to Vercel so it goes live,
confirm I can see it working in my browser, help me turn on Vercel's free
built-in visitor analytics, and then walk me through connecting my real
domain name from Hostinger to it.

8. Add a simple contact form to the site that emails me when someone fills
it out, using the Hostinger email settings from step 2. Make sure any secret
password goes into Vercel's private settings, never into the website files
or into this chat. Test it live with me.

9. Explain plainly that anytime I want to change anything later, I just come
back to this same chat, describe what I want, and you'll give me updated
text to paste into the right file on GitHub, which goes live automatically
within a couple minutes.

10. At the end, remind me what I now own, what it cost, and that if I ever
get stuck, I can call Paul at FreeholdTC dot dev, at seven seven four, two
four zero, four seven one five, for free help, no charge.

Let's start with step 1.
```

</details>
