# Spanish Vocabulary Learner

A mobile-friendly web application to help you learn Spanish vocabulary through flashcards, reading practice, and spaced repetition. Now with **500 common Spanish words** and advanced learning features!

## Features

### 1. Flashcards Mode
- Learn Spanish words with their English translations
- See example sentences in Spanish context
- **🔊 Audio pronunciation** - Hear the correct Spanish pronunciation
- **🌐 Translation toggle** - Switch between Spanish example and English translation
- Interactive card flipping
- Rate your knowledge (Got It! / Need Practice)
- **Choose batch size**: Study 25, 50, 100 words at a time, or all words

### 2. Reading Practice
- Read Spanish sentences with highlighted vocabulary words
- Test your understanding with multiple-choice questions
- Immediate feedback on your answers
- **Full sentence translation** displayed after answering
- Learn words in context
- Improved word highlighting (handles different word forms)

### 3. Progress Tracking
- View your learning statistics:
  - Total words studied
  - Words mastered
  - Overall accuracy percentage
  - Learning streak
- See detailed progress for each word (top 50 most practiced)
- Track which words need more practice

### 4. Spaced Repetition
- Smart review algorithm based on the SM-2 method
- Words you struggle with appear more frequently
- Words you know well are reviewed less often
- Optimal learning schedule automatically calculated
- Works with your selected batch size

## Vocabulary Database

The app includes **500 essential Spanish words** covering:
- Common greetings and phrases (20 words)
- Essential verbs in present tense (60 words)
- People and family members (30 words)
- Places and locations (30 words)
- Things and objects (40 words)
- Food and drink (40 words)
- Descriptive adjectives (60 words)
- Colors (15 words)
- Time and date expressions (35 words)
- Common adverbs and expressions (70 words)
- Pronouns and prepositions (40 words)
- Conjunctions and connectors (30 words)
- Other essential vocabulary (30 words)

**Every word includes:**
- Spanish word
- English translation
- Example sentence in Spanish
- English translation of the example sentence

## How to Use

### Getting Started
1. Open `index.html` in any modern web browser
2. No installation or server required!
3. Works offline after first load

### Learning Workflow

**Recommended Study Plan:**
1. Start with **Flashcards** mode to learn new words
2. Practice with **Reading** mode to see words in context
3. Check **Progress** tab to see which words need review
4. Return daily to review words due for spaced repetition

### Flashcards Mode
1. **Select your batch size** (25, 50, 100, or All words)
2. Read the Spanish word
3. Try to recall the English meaning
4. Tap the card to reveal the answer and example
5. **Click 🔊 Pronounce** to hear the Spanish pronunciation
6. **Click 🌐 Translation** to see the English translation of the example sentence
7. Rate yourself:
   - "Got It!" - You knew the answer (longer review interval)
   - "Need Practice" - You didn't know (review sooner)

### Reading Practice Mode
1. Read the Spanish sentence (with highlighted word)
2. Focus on the highlighted word
3. Choose the correct English meaning from options
4. Get immediate feedback
5. **See the full sentence translation** to understand the complete context
6. Click "Next Sentence" to continue

### Progress Tracking
- View your overall statistics
- See which words you've mastered (80%+ accuracy, 5+ reviews)
- Check your accuracy for each word
- Reset progress if you want to start fresh

## Technical Details

### Technologies
- Pure HTML, CSS, and JavaScript
- No dependencies or frameworks
- Fully client-side application
- LocalStorage for progress persistence

### Data Persistence
- Your progress is automatically saved to browser's LocalStorage
- Data persists across browser sessions
- To reset, use the "Reset All Progress" button in the Progress tab

### Mobile Responsive
- Optimized for mobile devices
- Touch-friendly interface
- Works on phones, tablets, and desktop

### Spaced Repetition Algorithm
The app uses a simplified SM-2 algorithm:
- First correct: Review in 1 day
- Second correct: Review in 6 days
- Subsequent: Interval × 2.5
- Incorrect: Reset to same-day review

## Customization

To add your own vocabulary words, edit the `vocabulary.js` file. Each word should include:

```javascript
{
  id: 501,
  spanish: "gato",
  english: "cat",
  example: "Mi gato es muy bonito.",
  translation: "My cat is very pretty."
}
```

**Important:** Always include both the Spanish example sentence AND its English translation for all features to work properly.

## Browser Compatibility

- Chrome/Edge: ✅ Full support (including Spanish pronunciation)
- Firefox: ✅ Full support (including Spanish pronunciation)
- Safari: ✅ Full support (including Spanish pronunciation)
- Mobile browsers: ✅ Full support (pronunciation quality varies by device)

**Note:** Audio pronunciation uses the Web Speech API. Spanish voices are available on most modern browsers. If no Spanish voice is available, the system will use the default voice.

## Privacy

- All data is stored locally in your browser
- No data is sent to any server
- No tracking or analytics
- Completely private and offline-capable

## Tips for Success

1. **Start small**: Begin with 25-50 words, then expand as you master them
2. **Consistency is key**: Study for 10-15 minutes daily
3. **Use all features**:
   - Listen to pronunciation to improve your accent
   - Read translations to understand sentence context
   - Use reading mode to see words in real sentences
4. **Focus on context**: Pay attention to example sentences and their translations
5. **Be honest**: Rate yourself accurately for better spaced repetition
6. **Review regularly**: Come back to review words when due
7. **Batch learning**: Master one batch before moving to the next for better retention

## License

This project is open source and available for educational purposes.

## Recent Updates

### Version 2.0
- ✅ Expanded to 500 common Spanish words
- ✅ Audio pronunciation with Web Speech API
- ✅ Translation toggle for example sentences in flashcards
- ✅ Full sentence translation in reading mode
- ✅ Batch size selection (25, 50, 100, or all words)
- ✅ Improved word highlighting in reading mode
- ✅ English translations for all example sentences

## Future Enhancements

Potential features for future versions:
- Verb conjugation practice
- More vocabulary categories (expand to 1000+ words)
- Custom word lists
- Export/import progress
- Multiple difficulty levels
- Grammar exercises
- Listening comprehension exercises
