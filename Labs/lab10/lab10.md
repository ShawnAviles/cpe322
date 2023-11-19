# CPE 322 - Lab 10

Lab provides students with knowledge about Blockchain concepts, in our case some hashing

## Run hash_value.py twice and compare results

<img width="961" alt="Screenshot 2023-11-19 at 3 03 52 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/46daef05-779c-489c-a6f7-7c49e457aefb">

- The first three hashes (hashes for 1, 1.0, 3.14) are identical. This is due to there being no seed set or new terminal being used so both runs are using the same default hash.
- The remaining hashes for the string, tuple, and object are all different. This is due to these data types being 'salted' with a random value by the Python interpretter. To prevent the randomness, a seed could be set but interestingly enough the reason for this is to prevent DOS attacks [[link to source](https://thepythoncorner.com/posts/2020-08-21-hash-tables-understanding-dictionaries/#)]

## SHA-2 Secure Hash Algorithm

<img width="615" alt="Screenshot 2023-11-19 at 3 05 50 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/c976427c-214e-44ca-8cf2-d0bd412a675b">


## Run snakecoin.py

<img width="818" alt="Screenshot 2023-11-19 at 3 07 37 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/84dd3bca-0463-427d-aabc-cdff45c76e6d">

<img width="406" alt="Screenshot 2023-11-19 at 3 07 48 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/2b2f2ef9-83bf-484e-9ba6-fce965695576">


## Run snakecoin-server-full-code.py on Terminal 1 and mine a new block on Terminal 2

<img width="862" alt="Screenshot 2023-11-19 at 3 09 35 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/13619bfc-c123-4942-9e9d-6399457462d9">

...

<img width="1512" alt="Screenshot 2023-11-19 at 3 11 03 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/bc967fa8-f5b0-42f5-852f-fdfdf24ad536">

<img width="810" alt="Screenshot 2023-11-19 at 3 11 30 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/8a02cdb4-82ad-4e17-8337-6dc5be0b848e">

Terminal 1

<img width="1512" alt="Screenshot 2023-11-19 at 3 11 15 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/30663e99-8dc3-4606-b7cc-0da7db8de3b5">

<img width="872" alt="Screenshot 2023-11-19 at 3 11 24 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/ed227bb4-c6d6-4c87-a195-0b82b994c289">

Terminal 2

## Clone Python blockchain app and uncomment the last line of node_server.py

<img width="826" alt="Screenshot 2023-11-19 at 3 40 57 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/118ccb37-32ed-4cc3-a94c-7909a1b9feac">


## Run node_server.py on Terminal 1 and run_app.py on Terminal 2

<img width="1510" alt="Screenshot 2023-11-19 at 3 18 40 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/93e72c13-5cfb-468c-a439-16a46c236a2a">

<img width="1512" alt="Screenshot 2023-11-19 at 3 19 29 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/c43eee95-f169-4b79-9ab2-2bb1eaa38c8d">

Terminal 1

<img width="869" alt="Screenshot 2023-11-19 at 3 22 39 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/4171f879-1ffa-4620-92e8-5467dfbdb384">

---

<img width="505" alt="Screenshot 2023-11-19 at 3 18 29 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/8ebb1189-5430-4b84-ac12-176369a273b7">

<img width="643" alt="Screenshot 2023-11-19 at 3 18 53 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/9526bc82-46cc-4e17-81cf-db64705ca9c9">

Terminal 2

<img width="867" alt="Screenshot 2023-11-19 at 3 22 29 AM" src="https://github.com/ShawnAviles/cpe322/assets/43704084/6beba7c2-0acf-46cd-9584-fc296598fe8b">



