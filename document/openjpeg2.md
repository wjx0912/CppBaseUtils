cd D:\test\pdfmate\3rd\openjpeg-2.3.1

mkdir build

cd build

cmake  -G  "Visual Studio 10"  -DCMAKE_BUILD_TYPE:string="Release" ../



然后vs2010打开OPENJPEG.sln：编译ALL_BUILD的win32 release&debug



=======================================================================



如果是vs2015，把上面的"Visual Studio 10"改为 "Visual Studio 14 2015"，如下：

cmake  -G  "Visual Studio 14 2015"  -DCMAKE_BUILD_TYPE:string="Release" ../
