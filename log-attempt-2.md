### Day 2: October 9, 2019 Wednesday

**Today's Progress**: I solved the last challenge question in Chapter 2 of Eloquent JS. It's the chessboard one. I couldn't solve it months ago. But coming back to it, I solved it rather quickly. Here's the solution: 

```let gridNum = Number(prompt("give me a number."));
for (let n = gridNum; n <= gridNum; n++) {
  let output = "# ";
  
  row = output.repeat(n/2);
  for (let c = 1; c <= gridNum; c++) {
    if (c % 2 == 1) {
      console.log(" " + row)
    }else{
    console.log(row);
    }
  }
} 
```

Here's my old code:
```for (let n = 8; n <= 8; n++) {
  let output = " #";
  
  row = output.repeat(n/2);
  for (let c = 1; c <= 8; c++) {
    console.log(row);
  }
}
```

**Thoughts** During my last attempt at 100DoC, I tried then skipped the question. So it's nice getting it done this time.


### Day 2: October 9, 2019 Wednesday

**Today's Progress**: I worked in Chapter 2 of Eloquent JavaScript, 3rd Edition. The chapter, Program Structure, is about where I left off; I wanted some overlap.

**Thoughts** None.


### Day 1: October 8, 2019 Tuesday

**Today's Progress**: I worked on PocketC. Haven't heard it? I'm not surprised. It had its shine around year 2000, I believe, for handheld and pocket PCs. It was supposedly a watered down version of C that was closer to VB and Java. I know neither VB, Java or C, so I can't back up that claim.

**Thoughts** PocketC isn't the language that I want to professionally program. That would be JavaScript. But PocketC is a language I want to crack. I thought it would be fun to lead with that before jumping back into web development. HTML, JavaScript, and CSS will be the focus of  this challenge. SQL if I'm lucky. Phaser if I'm well behaved. And node.js, or another framework, towards the end.
