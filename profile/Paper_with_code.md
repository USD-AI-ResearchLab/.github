<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; width:100%;">
  <thead>
    <tr>
      <th>Year</th>
      <th>Paper</th>
      <th>Code</th>
      <th>Submitted At</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>2025</td>
      <td><a href="link-to-paper.pdf">Deep Learning for Medical Imaging</a></td>
      <td><a href="https://github.com/example/repo">GitHub Repo</a></td>
      <td>CVPR 2025</td>
    </tr>
    <tr>
      <td>2024</td>
      <td><a href="link-to-paper.pdf">Robustness in AI Systems</a></td>
      <td><a href="https://github.com/example/repo2">GitHub Repo</a></td>
      <td>NeurIPS 2024</td>
    </tr>
    <tr>
      <td>2023</td>
      <td><a href="link-to-paper.pdf">Explainable AI for Healthcare</a></td>
      <td><a href="https://github.com/example/repo3">GitHub Repo</a></td>
      <td>AAAI 2023</td>
    </tr>
  </tbody>
</table>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cards Example</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      margin-top: 50px;
      background-color: #fff;
    }

    .card-container {
      display: flex;
      gap: 20px;
    }

    .card {
      width: 220px;
      border: 1px solid #e5e5e5;
      border-radius: 6px;
      padding: 16px;
      background-color: #f9fafa;
      box-shadow: 0 1px 2px rgba(0,0,0,0.05);
    }

    .card .icon {
      width: 20px;
      height: 20px;
      display: inline-block;
      border-radius: 50%;
      border: 2px solid #ccc;
      background-color: #f9fafa;
      margin-bottom: 12px;
      position: relative;
    }

    .card .icon::after {
      content: "✓";
      position: absolute;
      top: -3px;
      left: 3px;
      font-size: 16px;
      color: #bbb;
    }

    .card h4 {
      margin: 0;
      font-size: 15px;
      font-weight: bold;
      color: #333;
    }

    .card p {
      margin: 8px 0 0;
      font-size: 13px;
      color: #666;
    }
  </style>
</head>
<body>
  <div class="card-container">
    <div class="card">
      <div class="icon"></div>
      <h4>Invite your first member</h4>
      <p>Find people by their GitHub username or email address.</p>
    </div>
    <div class="card">
      <div class="icon"></div>
      <h4>Customize members' permissions</h4>
      <p>Set everyone’s base permissions for your code.</p>
    </div>
  </div>
</body>
</html>
