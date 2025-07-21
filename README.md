#I used the following code in Netlogo. I used the Simple Kinetic 1 model in Netlogo  
to react-forward
  if (any? other reactants-here) and
     ;; multiply k1 rate constant by the initial concentration of rate-limiting reactant - either PS or CIP - which is adjustable
     random-float 1 < (0.273 * number)
    [ ask one-of other reactants-here
        [ die ]
      set breed products
      set color red ]
<img width="468" height="187" alt="image" src="https://github.com/user-attachments/assets/6599acca-70c4-4816-8878-6632d476dcbf" />
