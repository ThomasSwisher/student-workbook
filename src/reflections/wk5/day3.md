# Daily Journal
Read Servers with Node/Express > MongoDb Relationships and answer the following questions
1. In simple terms what is a sub-document?

They are documents nested within other documents.

2. When might you use a sub-document?

Say you have a recipe you would save the ingredients as a sub set of the recipe.

3. How do you add to a collection of sub-documents? What about editing them?

If we wanted to add an ingredient: spaghetti we use const recipe.spaghetti = [{
  name: 'spaghetti',
  amount: '1 oz'
}]

To edit a collection of sub-documents you have to use findOne.
const spaghetti = await Ingredients.findOne({ name: 'spahetti' })
const spaghetti = ingredients.speghetti


https://thomasswisher.github.io/spring21-gregslist-server-v2/


