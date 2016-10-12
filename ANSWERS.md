## Questions

1. What is the difference between new and create for a model
New does not save the Model into the database
Create will save the new record into the database and return the corresponding model

2. What command combined with new will emulate the same behavior as create?
save 

3. What is the default integer column that exists on every table but we did NOT define?
timestamps


4. What single line of ruby code can insert a cat with the name "Kira" in the database?
Cat.create(:name 'Kira')

5. How did you like this homework in comparison with the previous homeworks?
At first I was extremeley confused with the migrations and how the model worked.
However, this was a good turning point for me in understanding how the other Controller and Views finally related to the database. 