1. Data Types:
   -Flashcard sets containing flashcards
   -Flashcard each has a question and answer
   -User profile possibly to remember their specific flashcard sets
2. Attributes:
   -Flashcard set:
       -title: Name of set
       -flashcards: Array holding flashcards
   -Flashcard
       -answer: the answer side of the flashcard
       -question: the question side of the flashcard
   -User Profile:
       -sets: a collection of the users owned flashcard sets
       -name: name of the user to display
       -userID: a unique identifier for the given user
3. Relationship Between Data:
    -The User creates flashcard sets, the flashcard sets contain flashcards, and the flashcards contain the study data
4. Data Sources:
    -Primarily user-input data; they input what they would like to study and that's almost excusively the data we store
