### Hi there 👋


- 🔭 I’m currently working on team project.
- 🌱 I’m currently learning IT tools
- Fork : [[https://github.com/AGH-Narzedzia-Informatyczne-2022-2023/Saranjil/fork]] 
### Paper
- The present paper aims at analysing the recently published Italian AI Strategy framing it within the context of the Italian IT industry. It references to data gathered in a small scale survey on AI adoption of Italian IT companies, and provides an analysis of the Italian AI Strategies focusing on the risks that its implementation will have to face and eventually draws three dierent scenarios on AI adoption in the Italian productive system.
-For the search I used keywords: AI
-Link [[ https://www.researchgate.net/publication/361064764_Perspectives_on_AI_adoption_in_Italy_the_role_of_the_Italian_AI_Strategy]]

### Code
# Print Pascal's Triangle in Python
from math import factorial
 
# input n
n = 5
for i in range(n):
    for j in range(n-i+1):
 
        # for left spacing
        print(end=" ")
 
    for j in range(i+1):
 
        # nCr = n!/((n-r)!*r!)
        print(factorial(i)//(factorial(j)*factorial(i-j)), end=" ")
 
    # for new line
    print()
