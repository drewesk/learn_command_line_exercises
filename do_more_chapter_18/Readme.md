
# Chapter 18: Looking inside files (grep)

## Do More

### Use quotes to find "new file" and "old file" and "This is".

> `chapter_18 Drew$ grep "new file" *.txt`
> `chapter_18 Drew$ grep "old file" *.txt`
> `chapter_18 Drew$ grep "This is" *.txt`

### Take the list of videos you created (or any other list) and use it to find some videos you want to find.

> `chapter_18 Drew$ pushd ~/temp/`
> `temp Drew$ grep "ruby_k" *.txt`
> `~/workspace/davinci_videos/in-class/ruby_koans.mp4`

### Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

> The man page also tells me that it makes the search case insensitive since grep is case sensitive by default.
