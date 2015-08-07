Conditional probabilities
=========================

P(But who am I, I need) ~ P(But who am I, I need)
                        P(but who am i i need)
                        = P(need | but who am i i) P(but who am i i)
                        ...
                        = P(need | but who am i i) * P(i | but who am i) * P (i | but who am) *
                          P(am | but who) * P(who | but) * P(but)
            (Markov)    = P(need | i) * P(i | i) * P(i | am) * P(am | who) * P(who | but) * P(but)

Log aproximation
================

Log(P(But who am I, I need)) ~ LogP(need | i) + LogP(i | i) + LogP(i | am) 
                                + LogP(am | who) + LogP(who | but) + LogP(but)
