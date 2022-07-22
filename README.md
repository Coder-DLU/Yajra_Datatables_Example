# Yajra_Datatables_Example Laravel9
Tạo mới project

```Dockerfile
composer create-project laravel/laravel Yajra_Datatables_Example
```

Trong bước này, chúng ta cần tạo  cài đặt yajra datatable thông qua  Composer, vì vậy một lệnh dưới đây của bạn là terminal và lệnh:

```Dockerfile
composer require yajra/laravel-datatables-oracle
```

Trong bước này, chúng ta cần tạo một vài users sử dụng tinker factory bằng lệnh sau 

```Dockerfile
php artisan tinker
User::factory()->count(20)->create()
```
Như sau:

```Dockerfile
PS C:\xampp\htdocs\Yajra_Datatables_Example> php artisan tinker
Psy Shell v0.11.7 (PHP 8.1.6 — cli) by Justin Hileman
>>> User::factory()->count(20)->create()                                                                                                                                                          
=> Illuminate\Database\Eloquent\Collection {#3635
     all: [
       App\Models\User {#3630
         name: "Moses Kerluke",
         email: "ward.lilyan@example.net",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "DgDOD9mj74",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 1,
       },
       App\Models\User {#3633
         name: "Ms. Dasia Rempel",
         email: "clemmie87@example.com",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "lIR1h9v4Qd",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 2,
       },
       App\Models\User {#3632
         name: "Vivien Satterfield",
         email: "xzavier.wehner@example.com",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "cmLQBkmJ2w",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 3,
       },
       App\Models\User {#3623
         name: "Lera Hamill I",
         email: "leif.kertzmann@example.com",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "2zdMgaAqBX",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 4,
       },
       App\Models\User {#3620
         name: "Miss River Olson",
         email: "autumn.legros@example.org",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "zkMOQ5Dfgv",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 5,
       },
       App\Models\User {#3629
         name: "Jenifer Littel V",
         email: "zemlak.willie@example.net",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "lblk0c5Tej",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 6,
       },
       App\Models\User {#3622
         name: "Dr. Hettie Toy Sr.",
         email: "jacobi.margaret@example.net",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "C0WeS7m1kM",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 7,
       },
       App\Models\User {#3592
         name: "Fay Weber",
         email: "bromaguera@example.net",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "IvwMduMQZj",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 8,
       },
       App\Models\User {#3588
         name: "Prof. Horace Hauck I",
         email: "jeanne40@example.org",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "kkPgG5nk4I",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 9,
       },
       App\Models\User {#3560
         name: "Karina Jast",
         email: "gisselle53@example.org",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "VYs2fK8zEC",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 10,
       },
       App\Models\User {#3559
         name: "Prof. Lamont Schneider IV",
         email: "khalid.funk@example.org",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "6GE2RnAJXn",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 11,
       },
       App\Models\User {#3558
         name: "Prof. Sienna Cartwright DDS",
         email: "rkub@example.org",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "JqmANsUjxg",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 12,
       },
       App\Models\User {#3557
         name: "Ms. Modesta Bogisich I",
         email: "kunze.jaycee@example.com",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "qd22aiYC7L",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 13,
       },
       App\Models\User {#3591
         name: "Dr. Branson Zieme MD",
         email: "sophie.purdy@example.org",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "2vHHy1hfy6",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 14,
       },
       App\Models\User {#3590
         name: "Miss Carolyn Tromp I",
         email: "thessel@example.net",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "fr7oACwIuU",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 15,
       },
       App\Models\User {#3589
         name: "Cristian Kassulke",
         email: "ida.kutch@example.org",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "fEzcRj5YO7",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 16,
       },
       App\Models\User {#3587
         name: "Dr. Cordie Toy",
         email: "dmccullough@example.net",
         email_verified_at: "2022-07-22 01:53:32",
         #password: "$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi",
         #remember_token: "Hn54MGgKgZ",
         updated_at: "2022-07-22 01:53:32",
         created_at: "2022-07-22 01:53:32",
         id: 17,
       },
       App\Models\User {#3586
         name: "Elijah Glover",
     ],
   }

>>>        
```

Tạo mới một Controller tên là UserController
- app/Http/Controllers/UserController.php

```Dockerfile
<?php
   
namespace App\Http\Controllers;
  
use Illuminate\Http\Request;
use App\Models\User;
use DataTables;
  
class UserController extends Controller
{
    /**
     * Display a listing of the resource.
     *
     * @return \Illuminate\Http\Response
     */
    public function index(Request $request)
    {
        if ($request->ajax()) {
            $data = User::select('*');
            return Datatables::of($data)
                    ->addIndexColumn()
                    ->addColumn('action', function($row){
       
                            $btn = '<a href="javascript:void(0)" class="edit btn btn-primary btn-sm">View</a>';
      
                            return $btn;
                    })
                    ->rawColumns(['action'])
                    ->make(true);
        }
          
        return view('users');
    }
}
```
Thêm route mới:
Trong bước này, chúng ta cần tạo route cho các tệp dữ liệu và một tuyến khác để lấy dữ liệu. vì vậy hãy mở tệp "route / web.php" của bạn và thêm route sau.
- routes/web.php

```Dockerfile
<?php
  
use Illuminate\Support\Facades\Route;
  
use App\Http\Controllers\UserController;
  
/*
|--------------------------------------------------------------------------
| Web Routes
|--------------------------------------------------------------------------
|
| Here is where you can register web routes for your application. These
| routes are loaded by the RouteServiceProvider within a group which
| contains the "web" middleware group. Now create something great!
|
*/
  
Route::get('users', [UserController::class, 'index'])->name('users.index');
```
Create Blade File: Trong bước cuối cùng, hãy tạo users.blade.php (resource / views / users.blade.php) cho layout  và chúng ta sẽ viết code ở đây: resources/views/users.blade.php

```Dockerfile
<!DOCTYPE html>
<html>
<head>
    <title>Laravel 9 Yajra Datatables Tutorial - ItSolutionStuff.com</title>
    <meta name="csrf-token" content="{{ csrf_token() }}">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.0.1/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.datatables.net/1.11.4/css/dataTables.bootstrap5.min.css" rel="stylesheet">
    <script src="https://code.jquery.com/jquery-3.5.1.js"></script>  
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-validate/1.19.0/jquery.validate.js"></script>
    <script src="https://cdn.datatables.net/1.11.4/js/jquery.dataTables.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <script src="https://cdn.datatables.net/1.11.4/js/dataTables.bootstrap5.min.js"></script>
</head>
<body>
     
<div class="container">
    <h1>Laravel 9 Yajra Datatables Tutorial - ItSolutionStuff.com</h1>
    <table class="table table-bordered data-table">
        <thead>
            <tr>
                <th>No</th>
                <th>Name</th>
                <th>Email</th>
                <th width="100px">Action</th>
            </tr>
        </thead>
        <tbody>
        </tbody>
    </table>
</div>
     
</body>
     
<script type="text/javascript">
  $(function () {
      
    var table = $('.data-table').DataTable({
        processing: true,
        serverSide: true,
        ajax: "{{ route('users.index') }}",
        columns: [
            {data: 'id', name: 'id'},
            {data: 'name', name: 'name'},
            {data: 'email', name: 'email'},
            {data: 'action', name: 'action', orderable: false, searchable: false},
        ]
    });
      
  });
</script>
</html>
```

Tất cả các bước cần thiết đã được thực hiện, bây giờ bạn phải nhập lệnh dưới đây và nhấn enter để chạy ứng dụng Laravel:

```Dockerfile
php artisan serve
```
php artisan serve

http://localhost:8000/users


![Container](a.png)


