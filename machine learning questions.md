# [How can we work in Machine learning field](https://www.reddit.com/r/coms30007/comments/do0828/any_books_recommendation/)

Oooh oooh! I'm not Carl, so maybe take my answer with a massive pinch of salt. But I compulsively buy a lot (a lot!) of books and then don't read them, so I feel totally qualified to jump in with an opinion here.

Don't buy a book (yet).

Actually for the things you asked about - they're all in the course textbook (Bishop), which is available for free online. I personally don't like the Bishop book because I have a different learning style where people have to explain things to me like I'm stupid first and then keep layering on the theory (i.e. progressively truer lies). If you start with some nice succinct vector calculus and use statements like "OBVIOUSLY the Hessian is poorly-conditioned LEFT TO THE READER LOL!" then I feel most unwelcome. Bishop... I've found it's only useful to me for things I already thought I knew. YMMV.


So I'm hoping I can answer your question because it's a bit like my constant question: How do I know what else I'm supposed to know? We only have a few weeks for this massive topic and Carl must obviously choose the points he hopes will last us a lifetime, and necessarily must leave out a whole lot of topics. How do I learn about the things I won't explicitly learn in this course?! Like a list of "things you should know when you're a real like Machine Learning practitioner"...

There's an unfortunate thing where you start being interested in Machine Learning (or even maybe are doing a MSc in machine learning already :-) ) and you feel like a total fraud because it seems like clearly everyone knows these OBVIOUSLY TOTALLY BASIC (?!) things that you've never heard of. Blog posts are all about Nesterov Momentum and RMSProp and Lipshitz Continuity but secretly you don't really know what gradient descent is and actually optimisation never even got a mention in your undergrad. People are blogging about Attention Mechanisms and Transformers and GRUs and you don't know what a "sequence model" (?) is. Lecturers talk about ICA being "like PCA" but you didn't know what PCA was and you Googled and OMFG Wikipedia was all about them eigenthingies and you thought that shit was behind you now (LOL SO WRONG!). You look ahead on modules' syllabuses and nobody seems to be about to tell you about these things in a structured fashion any time soon and it's all down to you to fake it till you make it. So it leaves you feeling vulnerable and freaked out. And maybe even a little bit angry - we all love to pay the £££ to just be made to feel stupid, right? Assuming you get through this, maybe you'll leave your degree "able to learn", with "the right foundations" but totally unable to answer a single mainstream interview question, nevermind actually sit with your ML/Data Science colleagues and solve problems using their vocabulary and toolbox of techniques. At what stage of your higher education were you going to learn this stuff, exactly? The Super PhD PostDoc? GAAAAAAH.

To which I say: chill. I feel like it's the right thing to just sip Carl's tasty Kool-aid right now, let the foundations settle, and stuff will come with time. We have so much time. Years and years.

That said, when you do want to know what the buzzwords mean, maybe by the end of your MSc degree, I think in addition to the things we have learned here already, you should probably know about the existence of stuff like:

- Generative vs Discriminative models, Classification vs Regression

- Underfitting, overfitting, bias-variance, regularisation, ROI curve analysis, F1 scores, train/test/validation data split, k-fold validation, uncovering and compensating for biases in data

- Linear Regression, Logistic Regression,Gaussian Process regression, SVMs, Naive Bayes

- Decision Trees, entropy, Random Forests, Gradient Boosting, Ensemble methods

- Clustering, K-means, kNN, Gaussian Mixture Models, the E-M algorithm, Markov Chains, HMMs, CRFs

- Dimensionality Reduction (t-SNE, PCA, ICA, DBSCAN)

- NLP (Natural Language Processing): LDA, Language models, Representation learning and embeddings, Word2Vec, FastText, BERT etc.

- ANNs & Deep Learning: Gradient Descent, back-propagation, Dropout, Regularisation, Adam, RMSProp, Densely connected FF nets, CNNs, the classic networks like AlexNet, VGG, Inception etc., YOLO. RNNs, LSTMs, GRUs, transformers, RBMs, Deep Belief Nets, Autoencoders & VAEs, GANs

- Reinforcement Learning: Q-learning, deep models like DQN etc.

Yes, in the real world people will expect you to have heard of this stuff and understand it at a shallow level in ML interviews and hopefully more deeply if they're paying you money to apply it for them. If your courses don't give you that, because there is only time for so many topics, then you need to find sources to learn more... like the Internet. It's useful to note that any knowledge you acquire rapidly decays and what you knew becomes unfashionable -- there's no one perfect course or book that will set you up for life.

A nice place to quickly learn about a lot of these concepts is The Hundred Page Machine Learning Book (http://themlbook.com/) which you can download chapter-by-chapter for free and then buy if you felt it was useful. It really succinctly covers a lot of the "mainstream" things.

Then I can absolutely recommend Andrew Ng's courses (the original Stanford CSS229 and CS230 courses, or maybe more accessible the Coursera versions) . Machine Learning is a bit dated and uses Matlab but the presentation is amazing I think. It has inspired literally millions of people. You have to pay for his newer deeplearning.ai ones, but not a lot. A little money will give you a comforting feeling that Deep Learning is not really quite as mysterious as all that and you can speak the lingo too.

Also great to feel quickly reassured about the basics: the free fast.ai courses: "Introduction to Machine Learning for Coders", "Practical Deep Learning for Coders", the follow-on "Deep Learning from the Foundations" and "A Code-First Introduction to Natural Language Processing".

I can also really recommend "Deep Learning with Python" by Francois Chollet (the Keras guy) if you want to start Deep Learning and like a practical approach.

And Chris Albon's Data Science flashcards (https://chrisalbon.com/) are a pretty good way to learn about the existence of concepts to learn more about.

But give the foundations - i.e. this ML course - a chance to format your brain correctly too and don't feel rushed to learn the other stuff at the same time. I feel like I'm filling in a lot of blanks on this course that should have been filled in a long time ago for me. It would have been nice to have them there first.
