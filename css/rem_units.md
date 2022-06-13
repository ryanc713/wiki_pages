# Sizing Elements using REM

REM stands for Root Element. When using rem units to size your text with, the value is $(n) times the root element size. To sum it up, using rem allows you to
set an initial font size on the `<html>` element, then the other components will base their size off that value. Here is an example:

````css
html {
  font-size: 16px;
}
h1 { 
  font-size: 2rem;          /* 32px */
}

p { 
  font-size: 1rem;          /* 16px */ 
}

li { 
  font-size: 1.5em;         /* 24px */
}
````


# Pixels to REM Reference with 16px Base Size

| Size in Pixels | Equivalent to this size in REM |
|----------------|--------------------------------|
| 10px | 0.625rem |
| 12px | 0.75rem |
| 14px | 0.875rem |
| 16px | 1rem(base) |
| 18px | 1.125rem |
| 20px | 1.25rem |
| 24px | 1.5rem |
| 30px | 1.875rem |
| 32px | 2rem |
