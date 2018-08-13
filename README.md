# Question-22

def pingPong(n):
    for i in range(n):
        if i >0:
            if(i%3 == 0):
                print("Ping") 
            if(i%7== 0):
                 print("Pong")

            if(i%3 == 0 and i%7 ==0):
             print("PingPong")

          else:
                pass
