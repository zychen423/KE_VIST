# KE_VIST
The code and output of our AAAI paper "Knowledge-Enriched Visual Storytelling"


## generated_stories
Unlike the format in VIST dataset, here we put all stories in a column. E.g.

```
{
        "original_text": "The local parish holds a craft show each year.",
        "album_id": "44277",
        "photo_flickr_id": "1741642",
        "story_id": "45530",
        "text_mapped_with_nouns_and_frame": [
            "parish_NOUN",
            "Containing_Frame",
            "craft_NOUN",
            "show_NOUN",
            "year_NOUN"
        ],
        "predicted_term_seq": [
            "Arriving_Frame",
            "town_NOUN"
        ],
        "predicted_story": "i was out of town . there were so many books to find . the table looked very old . we played games . it came from a man ."
```

`predicted_term_seq` is either the terms predicted from our image2term module(in this example) or . `predicted_story` is the whole story predicted by our term2story model, and `text_mapped_with_nouns_and_frame` is the result open-seasame extracted from original sentence.
