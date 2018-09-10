# rnn_seq2seq_pytorch
rnn encoder decoder and add attention using pytorch

output:
Reading lines...
Read 154883 sentence pairs
Trimmed to 11885 sentence pairs
Counting words...
Counted words:
fra 4714
eng 3081
['nous ne sommes pas encore desesperes .', 'we re not desperate yet .']
0m 23s (- 1m 34s) (500 20%) 3.7331
0m 51s (- 1m 16s) (1000 40%) 3.3684
1m 17s (- 0m 51s) (1500 60%) 3.0754
1m 44s (- 0m 26s) (2000 80%) 2.9269
2m 7s (- 0m 0s) (2500 100%) 2.8540
> nous ratons quelque chose ici .
= we re missing something here .
< we re going to . . . . <EOS>

> vous n etes pas un perdant .
= you re not a loser .
< you re not very . . . <EOS>

> je suis sur que c est faux .
= i m sure that s wrong .
< i m glad to to you . . . <EOS>

> il est devant la porte .
= he is in front of the door .
< he is a of . . . . <EOS>

> vous etes imprudents .
= you re foolish .
< you re very . . <EOS>

> il est dote de nombreux talents .
= he is endowed with many talents .
< he is a of of . . . <EOS>

> vous etes plus intelligente que moi .
= you re smarter than me .
< you re so that . <EOS>

> j ai honte de votre conduite .
= i am ashamed of your conduct .
< i m going to to . . . . <EOS>

> tu es bourre !
= you are drunk !
< you re very . . . <EOS>

> ils sont la .
= they are here .
< they re a . . . <EOS>

attentions.numpy() (10, 10)

input = elle a cinq ans de moins que moi .
output = she s a of . . . . <EOS>
input = elle est trop petit .
output = she s a of . . <EOS>
input = je ne crains pas de mourir .
output = i m not with . . <EOS>
input = c est un jeune directeur plein de talent .
output = he is a of . . . . . <EOS>
