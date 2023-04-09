# Fundamentals-of-Quantitative-Modeling
This course is available on Coursera, and here is my own note about this course.

## Module 1

### Definition and Uses of Models, Common Functions

#### What is a model?

* A formal ***description*** of a business process.
* It typically involves ***mathematical equations*** and random variables.
* It is almost always a ***simplification*** of a more complex structure.
* It typically relies upon a set of ***assumptions***.
* It is usually implemented in a ***computer program*** or using a spreadsheet.

#### Examples of models

* The price of a diamond as a function of its weight.
* The spread of an epidemic over time.
* The relationship between demand for, and price of a product.
* The uptake of a new product in a market.

#### Diamonds and weight

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/230770325-99d91daa-a7bf-4379-973e-083e45a9f46f.png>

#### Spread of an epidemic


<img width = 50% height = 50% src =https://user-images.githubusercontent.com/128298224/230770391-33370d55-acce-40c6-a60e-d8fc2ba69c62.png>

#### Demand models

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/230770433-138a7431-3099-4200-b20f-283a4b8c885f.png>

#### The uptake of a new product

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/230770481-ea47ee27-c42d-40ce-96d5-8a15015527dc.png>

### How models are used in practice

#### Ways to use models in practice

* Prediction: Calculating a single output: What's the expected price of a diamond ring that weighs 0.2 carats?
* Forecasting (time series): How many people are expected to be infected in 6 weeks?
* Optimisation: What price maximises profit?
* Ranking and targeting: Given limited resources, which potential diamonds for sale should be targeted first for potential purchase?
* Exploring what-if scenarios: If the growth rate of the epidemic increased to 20% per week, then how many infections would we expect in the next 10 weeks?
* Interpreting coefficients in model: What do we learn from the coefficient -2.5 in the price/demand model?
* Assessing how sensitive the model is to key assumptions.

#### Benefits of modeling

* Identify gaps in current understanding
* Make assumptions explicit
* Have a well-defined description of the business process
* Create an institutional memory
* Used as a decision support tool
* Serendipitous insight generator

### Key steps in the Modeling Process

#### Modeling Process Workflow

<img width = 75% height = 75% src = https://user-images.githubusercontent.com/128298224/230773640-82f4dcd2-f996-419d-8c74-61891071cf5e.png>

#### What if the model doesn't always work

* When the observed outcome differs greatly from the model's predicition, then there is the possibility of learning from thies event if we can understand why the difference occurs.
* Modeling is a continuous and evolutionary process
* We identify the weaknesses and limitations and iterate the modeling process to overcome them.

### A Vocabulary for Modeling

#### Data driven vs. theory driven

* ***Theory***: Given a set of assumptions and relations, then what are the logical consequences? E.g. If we assume that markets are efficient, then what should the price of a stock option be?
* ***Data***: Given a set of observations, how can we approximate the underlying process that generated them? E.g. I've separated out my profitable customers from the unprofitable ones. Now, what features are able to differentiate them?

#### Deterministic vs. probabilistic/stochastic

* ***Deterministic***: Given a fixed set of inputs, the model always gives the same output. E.g. Invest $1000 at 4% annual compound interest for 2 years. After 2 years the initial $1000 will always be worth $1081.60.
* ***Probabilistic***: Evven with identical inputs, the model output can vary from instance to instance. E.g. A person spends $1000 on lottery tickets. After the lottery is drawn how much they are worth dependes on a random variable, whether or not they won the lottery.

#### Discrete vs. continuous variables

* Watches can be digital or analog
* Likewise models can involve discrete or continuous variables. ***Discrete***: characterised by jumps and distinct values; ***Continuous***: a smooth process with an infinite number of potential values in any fixed interval.

#### Static vs. dynamic

* ***Static***: the model captures a single snapshot of the business process. E.g. Given a website's installed software base, what are the chances that it is compromised today?
* ***Dynamic***: the evolution of the process itself is of interest. The model describes the movement from state to state. E.g. Given a person's participation in a job training program, how long will it take until he/she finds a job and then, if they find one, for how long will they keep it?

### Mathematical Functions

#### Linear function

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/230774475-7ea3b045-9502-4053-ac08-643c29a9e670.png>

* $y = mx + b$
* Essential characteristic: the slope is constant.

#### The power function for various powers of $x$

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/230774533-708c55d7-d1d4-4d49-8f11-d7726f694a73.png>

* $y = x^{m}$.
* Essential characteristic: A one ***percent*** (proportionate) change in $x$ corresponds to an approximate $m$ ***percent*** (proportionate) change in $y$.

#### The exponential function

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/230774713-d46dae68-b138-4488-89d0-9556fdb9ac38.png>

* $y = e^{mx}$.
* Essential characteristic: the rate of change of $y$ is proportional to $y$ itself.
