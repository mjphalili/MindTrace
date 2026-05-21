# MindTrace
AI-powered book recommender that matches users to books based on mood, thinking style, and attention preferences. Combines enriched book data, semantic search, and LLM-based ranking to deliver personalized, context-aware recommendations with clear explanations beyond traditional genre-based systems.

As of May 1st, 2026, load google_books_dataset.csv to cleaner_script.ipynb to end up with cleanver_books_dataset.csv which can be used by the LLM (about 12k books)

As of May 5th, 2026, use CleanerP2 to fill in the moods and compute for reading times. Still 12497 books, end up with cleanver2_books.dataset.csv

As of May 6th, 2026, merged Uma's books + Google Books, used Merger.ipynb (adds books.csv), Refill.ipynb (fills in the mood etc.) and PublishDateFix.ipynb (separated exact published date and published_year since published_year is more complete). Books total is now 19054, end up with book_recommender_dataset.csv

As of May 21, 2026, you can open the BookID_Filler + dataset_WithID.zip file containing the dataset with complete 'book_ID' that we can use for matching and other steps for Tokenization.

As of May 21, 2026, the transformer and vector similarity search model is now working in Transformer_Vector_SimilaritySearch.ipynb
