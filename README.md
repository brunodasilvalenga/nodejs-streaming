# nodejs-streaming

Video streaming using nodejs

## Requirements

1. [Node](https://nodejs.org/)
2. [Express](https://expressjs.com/)


## Setup

1. **Clone the repo:**

  ```shell
  $ git clone https://github.com/brunovalenga/nodejs-straming.git
  $ cd nodejs-streaming
  ```

2. **Install dependencies** (npm v3+):
  
   ```shell
  $ npm install
  ```

3. **Create directory:**
  
  ```shell
  $ mkdir movies (Linux, OXS and Windows)
  ```
  
4. **Edit index.html:**
  
  Edit the file index.html in directory of the project and edit the attribute `src`

  ```html
  <video src="/movies/1.mp4" controls width="640" height="480"></video>
  ```

5. **Running:**

  ```shell
  $ node app.js
  ```
  
* Access: [http://localhost:3000/](http://localhost:3000/)
