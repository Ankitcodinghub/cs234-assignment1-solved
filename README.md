# cs234-assignment1-solved
**TO GET THIS SOLUTION VISIT:** [CS234 Assignment1 Solved](https://www.ankitcodinghub.com/product/cs234-assignment1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;64621&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS234 Assignment1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<h2>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flappy Karel MDP</h2>
There is a hot new mobile game on the market called Flappy Karel, where Karel the robot must dodge the red pillars of doom and flap its way to the green pasture. Consider the following 2 grid environments (Flappy World 1 and Flappy World 2). Starting from any unshaded square, Karel can either move right &amp; up, or right &amp; down (e.g from state 4 you can move to state 10 or 12, think checkers). Actions are deterministic and always succeed unless they will cause Karel to run into a wall. The thicker edges indicate walls, and attempting to move in the direction of a wall results in falling down one square (e.g. going in any direction from state 30 leads to falling into state 31). A successful run by Karel in Flappy World 1 is shown in Figure 1b. Taking any action from the green target squares (no. 32) earns a reward of <em>r<sub>g </sub></em>and ends the episode. Taking any action from the red squares of doom (no. 1, 7, 8, 12, 13…) earns a reward of <em>r<sub>r </sub></em>and ends the episode. Otherwise, from every other square, taking any action is associated with a reward <em>r<sub>s</sub></em>. Assume the discount factor <em>γ </em>= 0<em>.</em>9, <em>r<sub>g </sub></em>= +5, and <em>r<sub>r </sub></em>= −5 unless otherwise specified. Notice the Horizon is technically infinite in both worlds.

<table width="553">
<tbody>
<tr>
<td width="274">&nbsp;

<table width="236">
<tbody>
<tr>
<td width="47">1</td>
<td width="47">8</td>
<td width="47">15</td>
<td width="47">22</td>
<td width="47">29</td>
</tr>
<tr>
<td width="47">2</td>
<td width="47">9</td>
<td width="47">16</td>
<td width="47">23</td>
<td width="47">30</td>
</tr>
<tr>
<td width="47">3</td>
<td width="47">10</td>
<td width="47">17</td>
<td width="47">24</td>
<td width="47">31</td>
</tr>
<tr>
<td width="47">4</td>
<td width="47">11</td>
<td width="47">18</td>
<td width="47">25</td>
<td width="47">32</td>
</tr>
<tr>
<td width="47">5</td>
<td width="47">12</td>
<td width="47">19</td>
<td width="47">26</td>
<td width="47">33</td>
</tr>
<tr>
<td width="47">6</td>
<td width="47">13</td>
<td width="47">20</td>
<td width="47">27</td>
<td width="47">34</td>
</tr>
<tr>
<td width="47">7</td>
<td width="47">14</td>
<td width="47">21</td>
<td width="47">28</td>
<td width="47">35</td>
</tr>
</tbody>
</table>
</td>
<td width="279"></td>
</tr>
</tbody>
</table>
&nbsp;

Figure 1

<ul>
<li>Let <em>r<sub>s </sub></em>∈ {−4<em>,</em>−1<em>,</em>0<em>,</em>1}. Starting in square 2, for each of the possible values of <em>r<sub>s </sub></em>briefly explain what the optimal policy would be in Flappy World 1. In each case is the optimal policy unique and does the optimal policy depend on the value of the discount factor <em>γ</em>? Explain your answer. [5 pts]</li>
<li>What value of <em>r<sub>s </sub></em>would cause the optimal policy to return the shortest path to the green target square? Using this value of <em>r<sub>s </sub></em>find the optimal value function for each square in Flappy world 1. What is the optimal action from square 27? [5 pts]</li>
</ul>
Now consider Flappy world 2. It is the same as Flappy world 1, except there are no walls on the right and left sides. Going past the right end of flappy world 2 simply loops you to left hand side. Take a look at Figure 1b for a successful run by Karel in Flappy World 2.

(b) A successful run by Karel in Flappy World 2

(a) Flappy World 2

Figure 2

<ul>
<li>Let <em>r<sub>s </sub></em>∈ {−4<em>,</em>−1<em>,</em>0<em>,</em>1}. Starting in square 3, for each of the possible values of <em>r<sub>s </sub></em>briefly explain what the optimal policy would be in Flappy World 2. Using the value of <em>r<sub>s</sub></em>, that would cause the optimal policy to return the shortest path to the green target square, find the optimal value function for each square in Flappy world 2. What is the optimal action from square 27? [5 pts]</li>
<li>Consider a general MDP with rewards, and transitions. Consider a discount factor of <em>γ</em>. For this case assume that the horizon is infinite (so there is no termination). A policy <em>π </em>in this MDP induces a value function <em>V <sup>π </sup></em>(lets refer to this as). Now suppose we have the same MDP where all rewards have a constant <em>c </em>added to them and then have been scaled by a constant <em>a </em>(i.e. <em>r<sub>new </sub></em>= <em>a</em>(<em>c </em>+ <em>r<sub>old</sub></em>)). Can you come up with an expression for the new value function <em>V <sup>π </sup></em>induced by <em>π </em>in this second MDP in terms of <em>V<sub>old</sub><sup>π </sup>,c,a</em>, and <em>γ</em>? [5 pts]</li>
<li>Can scaling all the rewards by a fixed amount change the optimal policy of a MDP? If so, describe how different ranges of the constant <em>a </em>(where <em>r<sub>new </sub></em>= <em>a </em>∗ (<em>r<sub>old</sub></em>)) would change the optimal policy of the MDP from part (c). [5 pts]</li>
</ul>
<h2>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Applications of the Performance Difference Lemma</h2>
The purpose of this exercise is to get familiar on how to compare the value of different policies, <em>π</em><sub>1 </sub>and <em>π</em><sub>2</sub>, on a fixed horizon MDP. A fixed horizon MDP is an MDP where the agent’s state is reset after <em>H </em>timesteps; <em>H </em>is called the <em>horizon </em>of the MDP. There is no discount (i.e., <em>γ </em>= 1) and policies are allowed to be non-stationary, i.e., the action identified by a policy depends on the timestep in addition to the state. Let <em>x<sub>t </sub></em>∼ <em>π </em>denote the distribution over states at timestep <em>t </em>(for 1 ≤ <em>t </em>≤ <em>H</em>) upon following policy <em>π </em>and <em>V<sub>t</sub><sup>π</sup></em>(<em>x<sub>t</sub></em>) denote the value function of policy <em>π </em>in state <em>x<sub>t </sub></em>and timestep <em>t</em>, and <em>Q<sup>π</sup><sub>t </sub></em>(<em>x<sub>t</sub>,a</em>) denote the corresponding <em>Q </em>value associated to action <em>a</em>. As a clarifying example, we denote E<em>x<sub>t</sub></em><sub>∼<em>π</em></sub><sub>1</sub><em>V </em>(<em>x<sub>t</sub></em>) to represent the average value of the value function <em>V </em>(·) over the states at timestep <em>t </em>encountered upon following policy <em>π</em><sub>1</sub>. The following equality is called <em>performance</em>

<em>difference lemma </em>:

Intuition: The above expression can be interpreted in the following way. For concreteness, assume that <em>π</em><sub>1 </sub>is the better policy, i.e., achieving. Suppose you’re following policy <em>π</em><sub>2 </sub>and you are at timestep <em>t </em>in state <em>x<sub>t</sub></em>. You have the option to follow <em>π</em><sub>1 </sub>(the better policy) until the end of the episode, totalling &nbsp;return from the current state-timestep; or you have the option to follow <em>π</em><sub>2 </sub>for one timestep and then follow <em>π</em><sub>1 </sub>instead until the end of the episode (you can follow many other policies of course). This would give you a “loss” of <em>Q<sup>π</sup><sub>t </sub></em><sup>1</sup>(<em>x<sub>t</sub>,π</em><sub>1</sub>(<em>x<sub>t</sub>,t</em>)) − <em>Q<sup>π</sup><sub>t </sub></em><sup>1</sup>(<em>x<sub>t</sub>,π</em><sub>2</sub>(<em>x<sub>t</sub>,t</em>)) that originates from following the worse policy <em>π</em><sub>2 </sub>instead of <em>π</em><sub>1 </sub>in that timestep. Then the equation above means that the value difference of the two policies is the sum of all the losses induced by following the suboptimal policy for every timestep, weighted by the expected trajectory of the policy you’re following.

Question You will use the performance difference lemma to solve this problem. Consider an MDP where the state space S is partitioned into two sets of states S<sup>+ </sup>and its complement S<sup>+</sup>.

In every state <em>s </em>∈ S<sup>+ </sup>there exists an action <em>a</em><sup>+ </sup>that leads to the same state with probability 1 and gives a unitary reward:

<em>p</em>(<em>s<sub>t</sub></em><sub>+1 </sub>= <em>s </em>| <em>s<sub>t </sub></em>= <em>s,a<sub>t </sub></em>= <em>a</em><sup>+</sup>) = 1<em>,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; p</em>(<em>st </em>+ 1 6= <em>s </em>| <em>s<sub>t </sub></em>= <em>s,a<sub>t </sub></em>= <em>a</em><sup>+</sup>) = 0<em>.</em>

The reward function is always positive. In S<sup>+ </sup>the reward function equals 1 upon playing <em>a</em><sup>+ </sup>and <em>H </em>upon playing any action <em>a </em>6= <em>a</em><sup>+</sup>. Therefore in S<sup>+</sup>

<em>r</em>(<em>s,a</em><sup>+</sup>) = 1<em>,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; r</em>(<em>s,a</em>) = <em>H,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a </em>6= <em>a</em><sup>+</sup>

Conversely, in any state <em>s </em>6∈ <em>S</em><sup>+</sup>, the reward function is in [0<em>,</em>1] (∀<em>s </em>6∈ <em>S</em><sup>+ </sup>∀<em>a r</em>(<em>s,a</em>) ∈ [0<em>,</em>1]).

Consider a policy <em>π </em>and define a policy <em>π</em><sup>+ </sup>that takes action <em>a</em><sup>+ </sup>in any state S<sup>+ </sup>and is otherwise equal to <em>π</em>:

<em>π</em><sup>+</sup>(<em>s</em>) = <em>a</em><sup>+ </sup>if <em>s </em>∈ S<sup>+</sup><em>,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; π</em><sup>+</sup>(<em>s</em>) = <em>π</em>(<em>s</em>) if <em>s </em>∈ S6<sup>+</sup>

Intuitively, <em>π </em>accumulates higher return than <em>π</em><sup>+</sup>: in any state in S<sup>+ </sup>the policy <em>π</em><sup>+ </sup>chooses to take a unitary reward forever instead of a reward of <em>H </em>and then maybe more. Using the performance difference lemma show that at any state <em>s</em><sub>0</sub>

<em>.</em>

<h2>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Nonstationary Discount Factor <em>γ&nbsp;</em></h2>
In this problem you will consider a variable discount factor <em>γ</em>. In lecture 2, we proved that the Bellman backup is a contraction for <em>γ &lt; </em>1 in the infinity norm.

In this problem we consider having a non-stationary discount factor and assume you want to run <em>K </em>iterations of value iterations. Let <em>V<sub>K </sub></em>and <em>V<sub>K</sub></em><sup>0 </sup>be any two arbitrary initial value functions (at timestep <em>K</em>). The time-dependent Bellman backup operator <em>B<sub>k </sub></em>is defined as

<em>def&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em><sup>X </sup><sup>0</sup>|<em>s,a</em>)<em>V<sub>k</sub></em>(<em>s</em><sup>0</sup>)]

<em>V<sub>k</sub></em>−<sub>1 </sub>= <em>B<sub>k</sub>V<sub>k </sub></em>= max[<em>R</em>(<em>s,a</em>) + <em>γ<sub>k&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sub>p</em>(<em>s</em>

<em>a s</em><sup>0</sup>∈<em>S</em>

where

Notice that the value function index is decreasing: <em>K,K </em>− 1<em>,…,</em>2<em>,</em>1

10pt Similarly to what you’ve done in class, show that the Bellman operator with non-stationary discount factor at time step k is still a contraction, i.e.,

k<em>B<sub>k</sub>V </em>− <em>B<sub>k</sub>V </em><sup>0</sup>k<sub>∞ </sub>≤ <em>γ<sub>k</sub></em>k<em>V </em>− <em>V </em><sup>0</sup>k<sub>∞</sub>

10pt Using the above inequality prove that

k<em>B</em>1<em>B</em>2 ···<em>B</em><em>K</em><em>V</em><em>K </em>− <em>B</em>1<em>B</em>2 ···<em>B</em><em>K</em><em>V</em><em>K</em>0 k∞ ≤ <em>γ</em>1<em>γ</em>2 ···<em>γ</em><em>k</em>k<em>V</em><em>K </em>− <em>V</em><em>K</em>0 k∞

10pt Unfortunately <em>γ<sub>k </sub></em>≈ 1 when <em>k </em>is large so you cannot conclude that the convergence occurs exponentially fast. However, the error still shrinks: show that

which allows you to write

and ensure convergence, albeit at a slower rate.

<h2>4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Frozen Lake MDP</h2>
Now you will implement value iteration and policy iteration for the Frozen Lake environment from OpenAI Gym. We have provided custom versions of this environment in the starter code.

<ul>
<li>(coding) Read through vi_and_pi.py and implement policy_evaluation, policy_improvement and policy_iteration. The stopping tolerance (defined as max<em><sub>s </sub></em>|<em>V<sub>old</sub></em>(<em>s</em>) − <em>V<sub>new</sub></em>(<em>s</em>)|) is tol = 10<sup>−3 </sup>. Use <em>γ </em>= 0<em>.</em>9. Return the optimal value function and the optimal policy. [10pts]</li>
<li>(coding) Implement value_iteration in vi_and_pi.py. The stopping tolerance is tol =</li>
</ul>
10<sup>−3 </sup>. Use <em>γ </em>= 0<em>.</em>9. Return the optimal value function and the optimal policy. [10 pts]

<ul>
<li>(written) Run both methods on the Deterministic-4×4-FrozenLake-v0 and</li>
</ul>
Stochastic-4×4-FrozenLake-v0 environments. In the second environment, the dynamics of the world are stochastic. How does stochasticity affect the number of iterations required, and the

resulting policy? [5 pts]
