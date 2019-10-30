# Quora-Question-pair-similarity
Identify question pairs that have the same intent

Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute
unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. 
Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers
feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience 
to active seekers and writers, and offer more value to both of these groups in the long term.

The goal is to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts. The ground truth labels are inherently subjective, as the true meaning of sentences can never be known with certainty. Human labeling is also a 'noisy' process, and reasonable people will disagree. As a result, the ground truth labels on this dataset should be taken to be 'informed' but not 100% accurate, and may include incorrect labeling. We believe the labels, on the whole, to represent a reasonable consensus, but this may often not be true on a case by case basis for individual items in the dataset.
