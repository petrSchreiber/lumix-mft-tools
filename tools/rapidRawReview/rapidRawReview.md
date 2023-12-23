# Rapid RAW Review

Experimental tool to quickly evaluate results of your photoshoot and pick the best shots.

## How to use?
After launching the tool, you will be prompted to enter directory to start browsing photos in.

Initially, first 3 photos are loaded, to allow quick start. To pre-load all photos, press `F` key!

It works best with directory structures created by copyFromCard tool - pick the directory representing one day of shoot.

There is no UI to distract you, all controls are keyboard based.

### Navigating the photo list
- `D` - move to the next photo to the right
- `SHIFT` + `D` - move to the next *picked* photo to the right
- `A` - move to the next photo to the left
- `SHIFT` + `D` - move to the next *picked* photo to the left
- `W` - move back one day
- `D` - move forward one day
- `SPACE` - zooms in to the photo

### Non-destructive photo manipulation
- `C` - cycles through different crop presets
- `L` - forces landscape orientation
- `P` - forces portrait orientation

Photo manipulation operations do not alter the photo's in any way, but create metadata inside `.rapidRawReview` subdirectory.

### Rating
- `1` on Numlock - marks photo as *picked*, good shot
- `2` on Numlock - marks photo as not rated
- `3` on Numlock - marks photo as *rejected*, bad shot
- `X` - copies all *picked* photos to `EXPORT` subdirectory

Rating operations do not alter the photo's in any way, but create metadata inside `.rapidRawReview` subdirectory.

## Known limitations
- not optimized at all
- shows actually just jpeg preview stored in raw
- maximum of ~1000 concurrents RAW photos at the same time 

