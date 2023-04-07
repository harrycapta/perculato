# Accademia da leggere

>   [“DeepInsight: A methodology to transform a non-image data to an image for convolution neural network architecture”](https://www.nature.com/articles/s41598-019-47765-6). Using t-SNE to transform tabular data into images so computer vision methods can be used to model tabular data.

>   [“ResMLP: Feedforward networks for image classification with data-efficient training”](https://arxiv.org/abs/2105.03404). Building a functional image classification architecture without convolutions, attention, capsules — jut feedforward layers.

>   [“Single Headed Attention RNN: Stop Thinking With Your Head”](https://arxiv.org/abs/1911.11423). The funniest deep learning paper I have had the pleasure of coming across. Author Stephen Merity offers a humorous and insightful critique of modern Transformer-centric recurrent-ditching NLP research and proposes reconsidering the usefulness of recurrent layers.

>  [“GPT-D: Inducing Dementia-related Linguistic Anomalies by Deliberate Degradation of Artificial Neural Language Models”](https://aclanthology.org/2022.acl-long.131.pdf). Title says all.

>   [“Predictability and Surprise in AI Models”](https://facctconference.org/static/pdfs_2022/facct22-140.pdf). Really interesting theoretical and empirical analysis of the extent to which large language model behavior in an ‘OOD’ deployment context can be predictable/stable, and implications for AI public policy. (Who can really be held responsible for OOD AI behavior if AI itself is provably unstable in such a context?)
>   [“On the Opportunities and Risks of Foundation Models”](https://arxiv.org/pdf/2108.07258.pdf?utm_source=morning_brew). Landmark inter-disciplinary AI paper. Also, by far the most number of authors I have seen on an AI paper, ever.

>   [“A Mathematical Framework for Transformer Circuits”](https://transformer-circuits.pub/2021/framework/index.html). Ever wonder why Transformers — as conceptually simple as they are — work so well on such incredibly complex tasks? This great post by Anthropic’s research team begins building a mathematical framework for how Transformers work and why so well. (Turns out, Transformers have a mathematical analog for a `Ctrl+C Ctrl+V` ).

>   [“The Modern Mathematics of Deep Learning”](https://arxiv.org/abs/2105.04026). Deep learning has always been what I call an ‘empiricist-forward’ field: developments are generally made because someone tried some implementation out and it worked well rather than because a rigorous theory suggests it will work out. This has worked out decently so far, but theory is powerful. It gives us rigor. It gives us predictability. It lets us both understand _that_ things work and _why_. This paper is a difficult read but a great survey of such a theory of deep learning.

>   [“The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks”](https://arxiv.org/abs/1803.03635). Really important theoretical work emerging from the surprising success of pruning — a technique by which a computer vision or NLP model can be shrunk by between 5 to 20 times with minimal loss in performance — explaining how neural networks are trained and arrive at solutions.

>[“What’s Hidden in a Randomly Weighted Neural Network?”](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ramanujan_Whats_Hidden_in_a_Randomly_Weighted_Neural_Network_CVPR_2020_paper.pdf). Building upon the Lottery Ticket Hypothesis, this paper shows that you can discover a subnetwork within a large randomly initialized network which performs just as well as if that large neural network was trained. The subnetwork’s weights are not trained at all! A fascinating experiment which reveals a lot about the nature of large neural networks.

>[“Adversarial Examples Are Not Bugs, They Are Features”](https://arxiv.org/pdf/1905.02175.pdf). A unique take on a phenomena which has troubled AI researchers and thinkers since their discovery.

>[“Learning in High Dimension Always Amounts to Extrapolation”](https://arxiv.org/pdf/2110.09485.pdf). A series of experiments showing how the distinction between interpolation and extrapolation becomes incredibly blurry in the high-dimensional spaces neural networks operate on.

>[“Emergence of Grounded Compositional Language in Multi-Agent Populations”](https://arxiv.org/abs/1703.04908). Rather than training large language models to model human language, we allow agents to ‘create’ both the generation and interpretation of a synthetic language used to solve tasks which require inter-agent comunication.

>[“Moving beyond ‘algorithmic bias is a data problem’”](https://www.cell.com/patterns/fulltext/S2666-3899(21)00061-1). A really interesting and much needed response to the prevalent idea that the GIGO (Garbage-In, Garbage-Out) paradigm is really all there is to AI Fairness.

>[“Language Models as Knowledge Bases?”](https://aclanthology.org/D19-1250.pdf). Ask GPT-3 if it knows the year Lincoln was born in; ask it how many countries there are in Africa; ask it the conversion rate from Fahrenheit to Celsius; and it will tell you the answer to all of them. (It, however, cannot accurately tell you the answer to arithmetic problems like 4 + 8.) Can we interpret large language models as fluid, continuous knowledge bases which have an incredible quantity of human knowledge stored in fluid weights?

>[“An Attention Free Transformer”](https://arxiv.org/pdf/2105.14103.pdf). What happens when we remove attention — what many consider to be the most defining characteristic of the Transformer architecture — from a Transformer model? The result: a potentially more memory-efficient model which works both on image and NLP tasks.

>[“Transformers are Graph Neural Networks”](https://thegradient.pub/transformers-are-graph-neural-networks/). A novel interpretation of Transformers.

>[“Learning to learn by gradient descent by gradient descent”](https://arxiv.org/pdf/1606.04474.pdf). We’re all used to optimizing neural networks with gradient descent. How about optimizing gradient descent with gradient descent?

>[“Generating Words from Embeddings”](https://rajatvd.github.io/Generating-Words-From-Embeddings/). In most NLP models, words are associated with embeddings. What if we interpolate between embeddings to generate new nonsensical but realistic-sounding words?

>[“On Exact Computation with an Infinitely Wide Neural Net”](https://arxiv.org/pdf/1904.11955.pdf). A theoretically informed work which helps us understand the limits of network scaling.
>[“On the Measure of Intelligence”](https://arxiv.org/pdf/1911.01547.pdf). An essential novel work proposing an equation for the intelligence of a system, with plently of quantiative and philosophical theoretical discussion. Additionally, proposes a concrete benchmark task to develop and optimize models on.

>[“Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning”](https://arxiv.org/pdf/1506.02142.pdf). A novel interpretation of a time-honored mechanism.

>[“Model soups: averaging weights of multiple fine-tuned models improves accuracy without increasing inference time”](https://arxiv.org/abs/2203.05482). An interesting approach to model training which suggests that simply averaging the weights of various fine-tuned versions of a model can lead to performance gains.

>[“Deep physical neural networks trained with backpropagation”](https://www.nature.com/articles/s41586-021-04223-6). What more is there to say?

[[Notes]]