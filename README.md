# Prisoners-Dilemma
1.3.9 Prisoners Dilemma
elif player == 20:
        if getting_team_name:
            return 'SRamachandran'
        else:
            if len(opponent_history)==0: #It's the first round: collude
                return 'c'
            elif history[-1]=='c' and opponent_history[-1]=='b'or history[-1]=='b' and opponent_history[-1]=='b':
                return 'b' # betray is they were severely punished last time
            else:
                return 'c' #otherwise collude
            
    
