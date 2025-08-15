# Leveraging Machine Learning as a Mechanical Engineer 

I have been interested in the intersection of engineering simulation and physics-based machine learning for many years.  My background is in nonlinear structural finite element analysis, and machine learning was a natural step.  My first exposure to ML came around 2014, when I leanred about K-Means Clustering to group elements in a model by their stress-strain definition for conitnued simulation using another software package.  The initial simulation was a welding simulation with a moving heatsource.  The metallurgical phases in the heat affected zone and solidified region had property definitions based on heat exposure and cooling rates - every element in the HAZ and weld bead had a different stress-strain curve!  This level of detail was not feasible for continuation analysis in another FE package, so I used K-Means Clustering to group elements with similar stress-strain curves.

I created my first end-to-end FEA-surrogate model in early 2022, which entailed Abaqus scripting, Python routines to extract and organize data, surrogate model definition in Tensorflow, and an optimization wrapper in SciPy.  I had used many of these tools individually prior to this project.  Since then, I have explored PINNs and MeshGraphNets for different types of problems.  I have also explored 3d CNNs for flaw detection of CT-Scanned parts.

Outside of work, I am contributing to a couple research papers in the medical field by creating tile datasets and fine-tuning EfficientNet CNNs (more on that soon).  

Check out my portfolio for several example projects!

## Education

- MS in Mechanical Engineering, Univeristy of Notre Dame
- BS in Mechanical Engineering, University of Notre Dame

## Connect with me

- LinkedIn: [Brian Shula](https://www.linkedin.com/in/brianshula/)

<!--
**brians1982/brians1982** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
