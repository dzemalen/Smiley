# Smiley
hode = circle(60, "solid", "yellow")
mun = rectangle(30, 5, "solid", "black")
eye1 = circle(11, "solid", "white")
eye2 = circle(11, "solid", "white")
pup1 = circle(6, "solid", "darkblue")
pup2 = circle(6, "solid", "darkblue")
sc1 = rectangle(3, 7, "solid", "black")
sc2 = rectangle(3, 7, "solid", "black")
sc3 = rectangle(7, 3, "solid", "black")

emoji = 
  put-image(sc3, 45, 105,
    put-image(sc2, 43, 100,
      put-image(sc1, 47,110,
        put-image(pup2, 50, 80,
          put-image(pup1, 82, 80,
            put-image(eye2, 47, 80,
              put-image(eye1, 80, 80,
                put-image(mun, 65, 50,
                  hode))))))))
emoji
