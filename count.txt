void setup()
{
  // define pin modes
  // You need to code ontop of output being HIGH / OUTPUT
  
 pinMode(9,OUTPUT);
 pinMode(8,OUTPUT);
 pinMode(7,OUTPUT);
 pinMode(5,OUTPUT);
 pinMode(4,OUTPUT);
 pinMode(3,OUTPUT);
 pinMode(2,OUTPUT);
 
}

void loop() 
{
// • • loop to turn leds of 7seg ON
// >>>>>> ONE ...
  for(int i = 2; i < 10; i++)
    {
      if (i == 2 || i == 3) {
      pinMode(i,OUTPUT);
      }
      else 
      {
        pinMode(i,LOW);
        }
    }
  delay(1000);
  
// >>>>>> TWO ...
  for(int i = 2; i < 10; i++)
    {
      if (i == 3 || i == 4 || i == 6) {
      pinMode(i,LOW);
      }
      else 
      {
        pinMode(i,OUTPUT);
        }
    }
    delay(1000);

// >>>>>> THREE ...
  for(int i = 2; i < 10; i++)
    {
      if (i == 4 || i == 6 || i == 8) {
      pinMode(i,LOW);
      }
      else 
      {
        pinMode(i,OUTPUT);
        }
    }
    delay(1000);

// >>>>>> FOUR ...
  for(int i = 2; i < 10; i++)
    {
      if (i == 5 || i == 6 || i == 8 || i == 9) {
      pinMode(i,LOW);
      }
      else 
      {
        pinMode(i,OUTPUT);
        }
    }
    delay(1000);

// >>>>>> FIVE ...
  for(int i = 2; i < 10; i++)
    {
      if (i == 2 || i == 6 || i == 8) {
      pinMode(i,LOW);
      }
      else 
      {
        pinMode(i,OUTPUT);
        }
    }
    delay(1000);

// >>>>>> SIX ...
  for(int i = 2; i < 10; i++)
    {
      if (i == 2 || i == 6) {
      pinMode(i,LOW);
      }
      else 
      {
        pinMode(i,OUTPUT);
        }
    }
    delay(1000);

// >>>>>> SEVEN ...
  for(int i = 2; i < 10; i++)
    {
      if (i == 2 || i == 3 || i == 9 && i != 6) {
      pinMode(i,OUTPUT);
      }
      else 
      {
        pinMode(i,LOW);
        }
    }
    delay(1000);

// >>>>>> EIGHT ...
  for(int i = 2; i < 10; i++)
    {
      if (i != 6) {
      pinMode(i,OUTPUT);
      }
      else 
      {
        pinMode(i,LOW);
        }
    }
    delay(1000);

// >>>>>> NINE ...
  for(int i = 2; i < 10; i++)
    {
      if (i != 8 && i != 6) {
      pinMode(i,OUTPUT);
      }
      else 
      {
        pinMode(i,LOW);
        }
    }
    delay(1000);

// >>>>>> ZERO ...
  for(int i = 2; i < 10; i++)
    {
      if (i != 7 && i != 6) {
      pinMode(i,OUTPUT);
      }
      else 
      {
        pinMode(i,LOW);
        }
    }
    delay(10000);
   
}
