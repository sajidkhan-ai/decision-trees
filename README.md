🌱 Decision Trees: From Basics to Pruning

When I first started exploring Decision Trees, I was fascinated by how a simple "yes/no" style of questioning could break down even complex datasets. It almost felt like the algorithm was playing “20 Questions” with the data.

So, I picked the Iris dataset — the classic playground for machine learning beginners. At first, I trained a Decision Tree without any restrictions, and as expected, it tried to grow as much as possible. But soon, I noticed something interesting:

At deeper levels, the tree started creating sub-branches even when the decision was already clear.

For example, if one branch had values like [0, 36, 1], the majority class was obvious — we didn’t need more splits.

That’s when I learned about Post-pruning 🌳✂️

Instead of letting the tree grow endlessly, I introduced the hyperparameter max_depth. By controlling how deep the tree could go, I was able to simplify the model without losing accuracy — in fact, it made the tree more interpretable and avoided overfitting.

🚀 What’s inside this repo?

Decision Tree Classifier on Iris dataset – with and without pruning.

Hands-on exploration of max_depth and its impact.

A step towards model generalization and avoiding overfitting.

🔮 What’s next?

This is just the beginning. I’ll be experimenting with:

Other hyperparameters like min_samples_split, min_samples_leaf, etc.

Applying Decision Trees on a regression problem.

Comparing results across datasets to see how pruning strategies differ.

📝 Why I built this

I believe learning ML isn’t just about applying algorithms — it’s about understanding their behavior. By experimenting, observing, and storytelling, I’m making my journey more fun and hopefully inspiring others who are also starting out.
