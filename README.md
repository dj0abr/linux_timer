# linux_timer
Timer for various use, calls a function every xxx milliseconds

## Usage

```
int t1,t2;

void t1func()
{
    printf("Timer-1\n");
}

void t2func()
{
    printf("Timer-2\n");
}

int main()
{
    printf("Timer Test\n");

    t1 = start_timer(500, t1func);
    t2 = start_timer(1000, t2func);

    sleep_ms(5000);

    stop_timer(timer1);
    stop_timer(timer2);
    
    return 0;
}

```
