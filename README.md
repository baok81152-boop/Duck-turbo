<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Đua Vịt</title>

<style>
* {
  box-sizing: border-box;
  user-select: none;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #7ed6df;
  text-align: center;
  overflow: hidden;
}

h1 {
  margin: 12px 0;
  color: white;
  text-shadow: 2px 2px #555;
}

#game {
  width: 95%;
  max-width: 600px;
  height: 520px;
  margin: auto;
  background: #55a630;
  border: 5px solid white;
  border-radius: 15px;
  position: relative;
  overflow: hidden;
}

.lane {
  height: 100px;
  border-bottom: 4px dashed white;
  position: relative;
}

.duck {
  position: absolute;
  left: 10px;
  top: 20px;
  font-size: 55px;
  transition: left 0.15s linear;
}

.finish
