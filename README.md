# JavaScriptQustions

#Count vowels in a string

const vowelCount = (str) => {
  let count = 0;
  for(let char = 0 ; char <= str.length-1; char++){
  let ch = str[char].toLowerCase();
  if (ch === "a"|| ch === "e" || ch ==="i" || ch === "o"|| ch ==="u") {
    count++;
  }
  }
  return count;
}


console.log(vowelCount("adarishu"))
