 \project_{pizza} (
      ((\project_{name} Person)          // all people
       \diff
       (\project_{name}                  // people who frequent Dominos
           \select_{pizzeria='Dominos'}
                Frequents)
      \join Eats))                        // join with Eats to find pizzas1sttry

