# Spanish Vocabulary Learner

A mobile-friendly web application to help you learn Spanish vocabulary through flashcards, reading practice, and spaced repetition.

## Features

### 1. Flashcards Mode
- Learn Spanish words with their English translations
- See example sentences in Spanish context
- Interactive card flipping
- Rate your knowledge (Got It! / Need Practice)

### 2. Reading Practice
- Read Spanish sentences with highlighted vocabulary words
- Test your understanding with multiple-choice questions
- Immediate feedback on your answers
- Learn words in context

### 3. Progress Tracking
- View your learning statistics:
  - Total words studied
  - Words mastered
  - Overall accuracy percentage
  - Learning streak
- See detailed progress for each word
- Track which words need more practice

### 4. Spaced Repetition
- Smart review algorithm based on the SM-2 method
- Words you struggle with appear more frequently
- Words you know well are reviewed less often
- Optimal learning schedule automatically calculated

## Vocabulary Database

The app includes 80 essential Spanish words covering:
- Common greetings and phrases
- Basic nouns (family, objects, places)
- Essential adjectives (big, small, good, bad)
- Key verbs (to be, to have, to do, to go)
- Time expressions (day, night, always, never)
- Question words (where, when, how, why)

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
1. Read the Spanish word
2. Try to recall the English meaning
3. Tap the card to reveal the answer and example
4. Rate yourself:
   - "Got It!" - You knew the answer (longer review interval)
   - "Need Practice" - You didn't know (review sooner)

### Reading Practice Mode
1. Read the Spanish sentence
2. Focus on the highlighted word
3. Choose the correct English meaning from options
4. Get immediate feedback
5. Click "Next Sentence" to continue

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

To add your own vocabulary words, edit the `vocabulary` array in the JavaScript section:

```javascript
{
  id: 81,
  spanish: "gato",
  english: "cat",
  example: "Mi gato es muy bonito."
}
```

## Browser Compatibility

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Full support

## Privacy

- All data is stored locally in your browser
- No data is sent to any server
- No tracking or analytics
- Completely private and offline-capable

## Tips for Success

1. **Consistency is key**: Study for 10-15 minutes daily
2. **Use all three modes**: Combine flashcards, reading, and progress review
3. **Focus on context**: Pay attention to example sentences
4. **Be honest**: Rate yourself accurately for better spaced repetition
5. **Review regularly**: Come back to review words when due

## License

This project is open source and available for educational purposes.

## Future Enhancements

Potential features for future versions:
- Audio pronunciation
- More vocabulary categories
- Custom word lists
- Export/import progress
- Multiple difficulty levels
- Conjugation practice
