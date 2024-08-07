# P.A.G.U.R.I : Prompt Audio Generator User Research Investigation

![Paguri01](https://github.com/Pego43/PAGURI-Prompt-Audio-Generator-User-Research-Investigation/assets/48025739/0cda90b9-abce-4542-84bf-8cf68292879b)

## ABSTRACT

### English
The widespread use of artificial intelligence tools has simplified and enhanced numerous human activities, especially in creative processes in the field of music. In particular, the ability to transform textual descriptions into complex musical compositions is becoming a powerful tool increasingly accessible to everyone, since new  possibilities are emerging to allow users to create highly specific sounds based on their personal needs. However, the adoption of such tools remains limited, due to the lack of clear examples of user needs and the necessary requirements to meet their demands in the field of music creation.
The work of PAGURI, acronym for Prompt Audio Generator User Research Investigation, focuses on analyzing user behavior in the context of music and artificial intelligence tools for audio generation, with a particular focus on text-to-music. This study outlines the motivations behind the research, the tools used for the investigation, and describes the experiment conducted, in which a sample of individuals had the opportunity to use a text-to-music tool to generate audio from textual inputs and create personalized models with their own music. Finally, the results regarding the interaction between users and the text-to-music model will be presented, along with the related comments and suggestions on how and where these musical generation tools can find space and be employed to their fullest potential.

### Italiano
Il crescente impiego di strumenti di intelligenza artificiale ha semplificato e migliorato numerose attività umane, soprattutto nei processi creativi all’interno dell’ambito musicale. In particolare, la capacità di trasformare semplici descrizioni testuali in complesse composizioni musicali sta diventando un potente strumento di supporto sempre più accessibile a tutti,  poiché stanno emergendo nuove possibilità per consentire agli utenti che usufruiscono di questi mezzi di creare suoni altamente specifici soddisfacendo le proprie esigenze personali. Tuttavia, l’adozione di tali strumenti rimane ancora limitata, a causa della mancanza di chiari esempi di esigenze degli utenti e dei requisiti necessari per soddisfare le loro richieste all’interno del processo della creazione musicale.
Il lavoro di PAGURI, acronimo di Prompt Audio Generator User Research Investigation, si concentra sull’analisi del comportamento dell’utente nel contesto della musica e degli strumenti di intelligenza artificiale per la generazione audio, con particolare attenzione al text-to-music. Questo studio delinea le motivazioni alla base della ricerca, gli strumenti utilizzati per l’indagine, e descrive l’esperimento condotto in cui un campione di individui ha avuto l’opportunità di utilizzare un strumento text-to-music per generare audio da input testuali e creare modelli personalizzati con la propria musica. Verranno infine presentati i risultati pertinenti all’interazione tra gli utenti e il modello text-to-music, insieme ai relativi commenti e suggerimenti su come e dove questi strumenti di generazione musicale possono trovare spazio di utilizzo ed essere impiegati al massimo delle loro potenzialità.


## TODO LIST

- [x] Release abstract

- [x] Release code

- [x] Release dependencies

- [ ] Release setup tutorial


## INSTALL THE DEPENDENCIES

1 - Create an environment in conda : conda create -n myenvpaguri python=3.9

2 - Install Pytorch in your environment : conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia

3 - Fill in the following steps in the folder where you want to clone this repo:

  3.1 - git lfs install
  
  3.2 - git clone https://github.com/Pego43/PAGURI-Prompt-Audio-Generator-User-Research-Investigation.git
  
  3.3 - git lfs install
  
  3.4 - git clone https://huggingface.co/cvssp/audioldm-m-full
  
4 - Install the requirements : pip install -r requirements.txt
 
## ACKNOWLEDGMENTS
This code is heavely based on the following references : 

### Paper
[Investigating Personalization Methods in Text to Music Generation Generation](https://arxiv.org/abs/2309.11140)

### Code
[DreamSound](https://zelaki.github.io/)

[AudioLDM](https://github.com/haoheliu/AudioLDM)

[Diffusers](https://github.com/huggingface/diffusers) 
