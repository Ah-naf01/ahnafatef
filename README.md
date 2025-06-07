<p>&nbsp;</p><!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>নতুন দিগন্ত - ব্লাড ডোনেশন</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f8f9fa;
    }
    .footer {
      background-color: #dee2e6;
      text-align: center;
      padding: 10px;
      font-size: 14px;
    }
  </style>
</head>
<body>

<div class="container py-4">
  <h1 class="text-center text-danger mb-4">নতুন দিগন্ত</h1>
  <p class="text-center text-muted">একটি ব্লাড ডোনেশন প্ল্যাটফর্ম</p>

  <div class="row">
    <!-- Donor Registration -->
    <div class="col-md-6">
      <div class="card shadow-sm">
        <div class="card-header bg-danger text-white">
          রক্তদাতা রেজিস্ট্রেশন
        </div>
        <div class="card-body">
          <form method="POST" action="register.php">
            <div class="mb-2">
              <input type="text" name="name" class="form-control" placeholder="নাম" required>
            </div>
            <div class="mb-2">
              <input type="number" name="age" class="form-control" placeholder="বয়স" required>
            </div>
            <div class="mb-2">
              <select name="blood_group" class="form-select" required>
                <option value="">রক্তের গ্রুপ</option>
                <option>O+</option><option>O-</option><option>A+</option><option>A-</option>
                <option>B+</option><option>B-</option><option>AB+</option><option>AB-</option>
              </select>
            </div>
            <div class="mb-2">
              <input type="tel" name="phone" class="form-control" placeholder="মোবাইল নম্বর" required>
            </div>
            <div class="mb-3">
              <input type="text" name="district" class="form-control" placeholder="জেলা" required>
            </div>
            <button type="submit" class="btn btn-danger w-100">রেজিস্ট্রেশন করুন</button>
          </form>
        </div>
      </div>
    </div>

    <!-- Blood Search -->
    <div class="col-md-6 mt-4 mt-md-0">
      <div class="card shadow-sm">
        <div class="card-header bg-success text-white">
          রক্ত অনুসন্ধান
        </div>
        <div class="card-body">
          <form method="POST" action="search.php">
            <div class="mb-3">
              <select name="blood_group" class="form-select" required>
                <option value="">রক্তের গ্রুপ</option>
                <option>O+</option><option>O-</option><option>A+</option><option>A-</option>
                <option>B+</option><option>B-</option><option>AB+</option><option>AB-</option>
              </select>
            </div>
            <div class="mb-3">
              <input type="text" name="district" class="form-control" placeholder="জেলা লিখুন" required>
            </div>
            <button type="submit" class="btn btn-success w-100">অনুসন্ধান করুন</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="footer mt-4">
  Developed by Ahnaf Atef
</div>

</body>
</html># ahnafatef
