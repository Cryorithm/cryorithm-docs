# Cryorithm | Prompts | Apply 88-Column Word Wrapping in a Markdown Snippet

If you'd like to request GPT or any other model to handle Markdown formatting so that
lines are word-wrapped before reaching 88 columns, here's a prompt you can use:

## Prompt

```markdown
In my next message, I will send a string of Markdown-formatted text. Reformat the
string so that no line exceeds 88 characters in length. The text should maintain all
Markdown formatting and structural elements intact, including headers, lists, code
blocks, inline code, links, and images. The word wrapping should occur at space
characters unless a single word itself exceeds 88 characters, in which case the word
should remain on a line by itself. The output should preserve the integrity of Markdown
elements such as not breaking links or code syntax across lines.

## Requirements
1. **Line Length:** Ensure no line exceeds 88 characters.
2. **Preservation of Markdown Elements:** Maintain the integrity of all Markdown
     features:
   - Do not split inline code (`code`), links (`[text](URL)`), or images (`![alt text
     ](URL)`).
   - Keep code blocks (enclosed in triple backticks ```code```) intact without
     reformatting the internal content.
3. **Handling Long Words:** If a word itself is longer than 88 characters, it should
   be placed on its own line without breaking it.
4. **Consistency:** Ensure the output retains the same order and content of Markdown
   elements as the input, only altering line lengths.

## Examples

- Input: "Here is a sample line of text that needs to be wrapped according to the rules specified to demonstrate the desired functionality."
  - Output: "Here is a sample line of text that needs to be wrapped according to the rules\nspecified to demonstrate the desired functionality."
- Input: "A very-long-word-that-exceeds-eighty-eight-characters00000000000000000000000000000000000000000 should not be broken."
  - Output: "A very-long-word-that-exceeds-eighty-eight-characters00000000000000000000000000000000000000000\nshould not be broken."
```

## Instructions for Use
Use this prompt to process any Markdown text requiring specific line wrapping while
preserving all formatting and Markdown integrity. Adjust as necessary for different
Markdown flavors or specific content types.
