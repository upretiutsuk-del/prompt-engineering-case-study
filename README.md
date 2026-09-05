# Prompt iteration: mobile RPG key art

*Work in progress. Round 3 to come.*

A short record of how I work a text-to-image prompt from a vague first attempt to something that actually matches a brief. I picked a mobile game key art brief because it has real constraints: it has to read at thumbnail size, and it has to look like a store asset rather than generic fantasy art. Each round shows the prompt, what came back, what was wrong with it, and what I changed to fix it.

Generated in Gemini (Flash, image tool). Prompt restructuring worked out in Claude.

## The brief

App store key art for a fantasy mobile RPG. A lone battle-mage at the edge of a crumbling ruin at dusk, mid-cast, energy forming in one outstretched hand. It has to read clearly at thumbnail size: strong silhouette, one obvious focal point, premium mobile game look rather than generic fantasy art.

## Round 1

**Prompt**

```
fantasy mage casting a spell in ruins at sunset, mobile game art
```

![Round 1 output](images/round-1.jpg)

**What came back**

The thing I expected to fail was the thumbnail read, so I checked that first. I zoomed out until it was roughly icon-sized and it held up better than I thought it would. The glowing ring wrapped around her actually helps at that size. It marks where she is even when the detail is gone. So the silhouette is not the problem here, which surprised me.

What is a problem is that everything is glowing. The sunset, the swirl, the crystal on the staff, the cracks in the ground, the little runes, even the potion bottles on her belt. At full size nothing wins. My eye bounces around the frame and never lands. I asked for the magic to be in her hand, and instead it's a big ring wrapped around her whole body, which spreads it out even more.

Then there's the text on the arch. I never asked for text. It says something like "AURA ARCANA" with a couple of made-up letters mixed in. That alone kills it as an actual store asset.

The background is doing way too much. Two arches, moss, stairs, broken towers in the distance, full sunset. Nothing sits back.

And it's flat. There's no real dark anywhere in the picture. Everything is mid-brightness, evenly lit, which is why it feels like generic asset-store art instead of something you'd actually see on a store page.

Colours are fighting too. Purple sky, orange sun, blue magic, green moss. Four things at once.

Small stuff: her outstretched hand is a bit mushy up close, and the whole thing came out tall and poster-shaped, which wasn't a decision I made.

## Round 2

Round 1 had three things I wanted to fix: the invented text on the arch, the cluttered background, and the flatness. I also wanted the magic concentrated in her hand instead of wrapped around her whole body.

**Prompt**

```
Key art for a premium mobile fantasy RPG. A lone battle-mage stands at the
crumbling edge of a ruined stone platform at dusk, seen in a low-angle
three-quarter medium shot, mid-cast, with a single concentrated burst of blue
arcane energy igniting in one outstretched hand. Strong readable silhouette:
the figure is clearly separated from the background, dark cloak against an open
twilight sky, with nothing crossing or overlapping the body. The spell in the
hand is the only bright light source, casting hard rim light along the figure's
edge; deep shadows elsewhere with true blacks. Uncluttered background, with the
ruin falling off into atmospheric haze, minimal detail, no secondary structures
or distant towers. Restrained palette: deep teal and indigo, with the spell's
warm cyan as the single accent. Painterly semi-realistic rendering, high
contrast, cinematic, designed to read clearly at thumbnail size. No text, no
lettering, no runes, no glowing ground cracks, no distorted hands.
```

**The model's disclaimer**

Before showing the image, Gemini told me it had been unable to leave out the lettering on the archway, the glowing runes on the ground, or the background structures. Then it generated an image where the lettering and the runes are gone. The self-report was wrong. It was right about the background, which still has the arch and the stairs in it, but wrong about the other two. Worth remembering that what the model says about its own output is not evidence of what it did.

![Round 2 output](images/round-2.jpg)

**What came back**

The text is gone, which was the thing that made round 1 unusable. The arch is plain stone now. The ground runes are gone too.

The colours stopped fighting. It's teal and indigo with the cyan spell as the only accent, and it holds together as one image instead of four things competing.

The magic is a single burst in her hand instead of a ring around her body, so there's one clear place for your eye to land.

There's actual darkness in it now. Deep shadow in the arch, under the stairs, in the folds of her cloak. That's most of why it stopped looking like stock fantasy art.

What didn't work: the background is still busy. The arch is there, the stairs are there, and there's more structure in the haze on the right. I asked for none of that.

The framing instruction barely registered. I asked for a low-angle three-quarter medium shot. The angle is slightly lower than round 1, but it's still a tall full-body poster rather than the tighter framing I wanted.

The rim light is too subtle. There's a bit on her left arm and her hair, but her right side has almost nothing separating her from the background.

**The trade-off I didn't see coming**

I zoomed this one out to thumbnail size the same way I checked round 1, and it reads worse. Everything now sits in the same narrow band of dark teal, so at small sizes the figure and the background merge into one dark mass. Round 1 was ugly and cluttered but its bright sunset gave her something to stand against.

So fixing the clutter and the colour fight cost me the one thing the naive prompt was doing right, by accident. That's what round 3 has to reconcile.

## Round 3

*(to come)*

## What I learned

*(to come)*
