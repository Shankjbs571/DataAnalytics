# DataAnalytics

This Colab notebook contains my solutions for a DataAnalytics project that involved analyzing a dataset with the following questions:

1. **How many unique tags are there in the dataset [book_tags.csv]?** (Numerical)
2. **How many unique users are present in the dataset [ratings.csv]?** (Numerical)
3. **Which book (title) has the maximum number of ratings based on (work_ratings_count) [books.csv]?** (String)
4. **How many books do not have an original title [books.csv]?** (Numerical)
5. **How many unique books are present in the dataset?** Evaluate based on the 'book_id' [books.csv]. (Numerical)
6. **Which book (goodreads_book_id) has the least number of counts of tags given by the user, i.e., the book with the minimum user records including all tags [book_tags.csv]?** (Numerical)
7. **Which book (goodreads_book_id) is marked as to-read by most users [books.csv, toread.csv]?** (Numerical)
8. **What is the mean value of the rating of all the books in the dataset based on (average_rating) [books.csv]?** (Float)
9. **Which book (title) has the most number of counts of tags given by the user, i.e., the book with the maximum user records including all tags [book_tags.csv, books.csv]?** (String)
10. **Predict sentiment using Textblob. How many positive titles (original_title) are there [books.csv]?**

## Files

The dataset includes the following CSV files:

- **ratings.csv**: Contains ratings sorted by time. Ratings go from one to five. Both book IDs and user IDs are contiguous. For books, they are 1-10000, for users, 1-53424.
- **to_read.csv**: Provides IDs of the books marked "to read" by each user, as user_id, book_id pairs, sorted by time.
- **books.csv**: Has metadata for each book (goodreads IDs, authors, title, average rating, etc.). The metadata has been extracted from goodreads XML files.
- **book_tags.csv**: Contains tags/shelves/genres assigned by users to books. Tags in this file are represented by their IDs. Each book_id has multiple tag_id. The field "count" denotes ‘user records’ (the number of users tagged the given tag_id with the goodreads_book_id).

## Additional Information

These datasets contain a significant number of records, which provided a valuable learning experience in handling large datasets and pushed my skills to the next level.

.............
