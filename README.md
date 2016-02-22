# Room_allocator [![Build Status](https://travis-ci.org/andela-pwanjiru/Room_allocator.svg?branch=master)](https://travis-ci.org/andela-pwanjiru/Room_allocator) 
[![Coverage Status](https://coveralls.io/repos/github/andela-pwanjiru/Room_allocator/badge.svg?branch=master)](https://coveralls.io/github/andela-pwanjiru/Room_allocator?branch=master)


### Description

This is a system used to allocate offices and living spaces at Amity to Andela employees.

### Setting up the program :


Clone the repo

  ```bash
  git clone https://github.com/andela-pwanjiru/Room_allocator.git
  ```

### How to run

* To view the allocated offices
  ```bash
  python entry.py get_offices to 
  ```

* To view the allocated livingspaces
  ```bash
  python entry.py get_livingspaces
  ```

* To view members in a room
  ```bash
  python entry.py print members in <room name>
  ```

* To view the people not allocated offices
  ```bash
  python entry.py print unallocated employees
  ```

* To view all fellows without a livingspace.
  ```bash
  python entry.py print unallocated fellows
  ```

### How to run tests:
```bash
python test.py
```
