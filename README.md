# linux_timer
Timer for various usage, calls a function every xxx milliseconds

## Usage

```
int main()
{
    printf("Raspi Ham Radio Control Board starting ...\n");

    t1 = start_timer(500, t1func);
    t2 = start_timer(1000, t2func);

    sleep_ms(5000);

    return 0;
}

```
