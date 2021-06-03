user has_many courses
courses has_many users

has many through 
user has_many courses, through enrollments 
courses has_many users, through enrollments


has many one to many relationship
  one video has many comments 
  all comments belong to the video
has one, one to one relationship
  one person has a single address 

has many through, many to many relationship
  billboard has many song, through artist 
  songs has many billboard through artist