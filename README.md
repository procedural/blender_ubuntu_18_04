Blender v2.93.2 compiled on Ubuntu 18.04 x64 (without SSGI): https://github.com/procedural/blender_ubuntu_18_04/releases/tag/blender-v2.93-release-03d5c8b
---------------------------------------------------------------------------------------------------------------------------------------------

![](https://github.com/procedural/blender_ubuntu_18_04/raw/main/ssgi/blender-ssgi-ubuntu1804.png)

https://blenderartists.org/t/screen-space-global-illumination-for-eevee/1248355/409

```
$ gcc --version
gcc (Ubuntu 7.5.0-3ubuntu1~18.04) 7.5.0
```
```
$ clang --version
clang version 6.0.0-1ubuntu2 (tags/RELEASE_600/final)
Target: x86_64-pc-linux-gnu
Thread model: posix
InstalledDir: /usr/bin
```
https://github.com/procedural/blender/releases/tag/blender-v2.93-release-08-july-2021

https://wiki.blender.org/wiki/Building_Blender/Linux/Ubuntu
```
[100%] Linking CXX executable ../../bin/blender
/tmp/blender-git/lib/linux_centos7_x86_64/openvdb/lib/libopenvdb.a(Grid.cc.o): In function `openvdb::v8_0::GridBase::createGrid(std::string const&)':
Grid.cc:(.text+0x2671): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/openvdb/lib/libopenvdb.a(Grid.cc.o): In function `openvdb::v8_0::GridBase::registerGrid(std::string const&, std::shared_ptr<openvdb::v8_0::GridBase> (*)())':
Grid.cc:(.text+0x29cc): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/openvdb/lib/libopenvdb.a(Grid.cc.o): In function `openvdb::v8_0::math::ScaleTranslateMap::ScaleTranslateMap(openvdb::v8_0::math::Vec3<double> const&, openvdb::v8_0::math::Vec3<double> const&)':
Grid.cc:(.text._ZN7openvdb4v8_04math17ScaleTranslateMapC2ERKNS1_4Vec3IdEES6_[_ZN7openvdb4v8_04math17ScaleTranslateMapC5ERKNS1_4Vec3IdEES6_]+0x12d): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/openvdb/lib/libopenvdb.a(Grid.cc.o): In function `openvdb::v8_0::TypedMetadata<bool>::copy(openvdb::v8_0::Metadata const&)':
Grid.cc:(.text._ZN7openvdb4v8_013TypedMetadataIbE4copyERKNS0_8MetadataE[_ZN7openvdb4v8_013TypedMetadataIbE4copyERKNS0_8MetadataE]+0x5f): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/openvdb/lib/libopenvdb.a(Grid.cc.o): In function `openvdb::v8_0::TypedMetadata<long>::copy(openvdb::v8_0::Metadata const&)':
Grid.cc:(.text._ZN7openvdb4v8_013TypedMetadataIlE4copyERKNS0_8MetadataE[_ZN7openvdb4v8_013TypedMetadataIlE4copyERKNS0_8MetadataE]+0x60): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/openvdb/lib/libopenvdb.a(Grid.cc.o):Grid.cc:(.text._ZN7openvdb4v8_013TypedMetadataINS0_4math4Vec3IiEEE4copyERKNS0_8MetadataE[_ZN7openvdb4v8_013TypedMetadataINS0_4math4Vec3IiEEE4copyERKNS0_8MetadataE]+0x66): more undefined references to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(OCIOYaml.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::save(YAML::Emitter&, std::shared_ptr<OpenColorIO_v2_0::Transform const>, unsigned int)':
OCIOYaml.cpp:(.text+0xaef0): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(OCIOYaml.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::save(YAML::Emitter&, OpenColorIO_v2_0::Config const&)':
OCIOYaml.cpp:(.text+0xe8d8): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
OCIOYaml.cpp:(.text+0x10d24): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(OCIOYaml.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::CheckDuplicates(YAML::Node const&)':
OCIOYaml.cpp:(.text+0x119d9): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(OCIOYaml.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::load(YAML::Node const&, std::shared_ptr<OpenColorIO_v2_0::LogAffineTransform>&) [clone .constprop.0]':
OCIOYaml.cpp:(.text+0x12311): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(OCIOYaml.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::load(YAML::Node const&, std::shared_ptr<OpenColorIO_v2_0::LogCameraTransform>&) [clone .constprop.0]':
OCIOYaml.cpp:(.text+0x12949): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(OCIOYaml.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::load(YAML::Node const&, std::shared_ptr<OpenColorIO_v2_0::LogTransform>&) [clone .constprop.0]':
OCIOYaml.cpp:(.text+0x12e59): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(OCIOYaml.cpp.o):OCIOYaml.cpp:(.text+0x13619): more undefined references to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(OCIOYaml.cpp.o): In function `YAML::Node const YAML::Node::operator[]<char [21]>(char const (&) [21]) const':
OCIOYaml.cpp:(.text._ZNK4YAML4NodeixIA21_cEEKS0_RKT_[_ZNK4YAML4NodeixIA21_cEEKS0_RKT_]+0x6fe): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(Op.cpp.o): In function `OpenColorIO_v2_0::Op::getIdentityReplacement() const':
Op.cpp:(.text+0x5c32): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(GradingRGBCurve.cpp.o): In function `OpenColorIO_v2_0::GradingRGBCurveImpl::validate() const [clone .cold]':
GradingRGBCurve.cpp:(.text.unlikely+0xcf): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(GradingTone.cpp.o): In function `OpenColorIO_v2_0::GradingTone::validate() const':
GradingTone.cpp:(.text+0x20d9): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
GradingTone.cpp:(.text+0x261c): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
GradingTone.cpp:(.text+0x2685): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(GradingTone.cpp.o):GradingTone.cpp:(.text+0x26f1): more undefined references to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(FileFormatCTF.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::XMLParserHelper::EndElementHandler(void*, char const*)':
FileFormatCTF.cpp:(.text+0x1059): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
FileFormatCTF.cpp:(.text+0x1178): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
FileFormatCTF.cpp:(.text+0x11d0): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(FileFormatCTF.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::XMLParserHelper::StartElementHandler(void*, char const*, char const**)':
FileFormatCTF.cpp:(.text+0x5927): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(FileFormatCTF.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::LocalFileFormat::bake(OpenColorIO_v2_0::Baker const&, std::string const&, std::ostream&) const':
FileFormatCTF.cpp:(.text+0x66ce): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(FileFormatHDL.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::LocalFileFormat::read(std::istream&, std::string const&, OpenColorIO_v2_0::Interpolation) const':
FileFormatHDL.cpp:(.text+0x4b12): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
FileFormatHDL.cpp:(.text+0x4bae): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
FileFormatHDL.cpp:(.text+0x4d3f): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(FileFormatHDL.cpp.o):FileFormatHDL.cpp:(.text+0x4e71): more undefined references to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(CTFTransform.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::FixedFunctionWriter::getAttributes(std::vector<std::pair<std::string, std::string>, std::allocator<std::pair<std::string, std::string> > >&) const':
CTFTransform.cpp:(.text+0x7548): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(CTFTransform.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::GradingPrimaryWriter::writeRGBM(char const*, OpenColorIO_v2_0::GradingRGBM const&, OpenColorIO_v2_0::GradingRGBM const&) const [clone .isra.0]':
CTFTransform.cpp:(.text+0x8b89): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
CTFTransform.cpp:(.text+0x8c8a): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(CTFTransform.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::GradingToneWriter::writeRGBMSW(char const*, OpenColorIO_v2_0::GradingRGBMSW const&, OpenColorIO_v2_0::GradingRGBMSW const&, bool, bool) const':
CTFTransform.cpp:(.text+0xa5fc): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libOpenColorIO.a(CTFTransform.cpp.o): In function `OpenColorIO_v2_0::(anonymous namespace)::GradingRGBCurveWriter::writeContent() const':
CTFTransform.cpp:(.text+0xecc5): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/opencolorio/lib/libyaml-cpp.a(exp.cpp.o): In function `YAML::Exp::Escape(YAML::Stream&)':
exp.cpp:(.text+0xd20): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/osl/lib/liboslcomp.a(oslcomp.cpp.o): In function `OSL_v1_11::pvt::find_stdoslpath(std::vector<std::string, std::allocator<std::string> > const&)':
oslcomp.cpp:(.text+0x1eec): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/osl/lib/liboslcomp.a(oslcomp.cpp.o): In function `OSL_v1_11::pvt::OSLCompilerImpl::write_oso_symbol(OSL_v1_11::pvt::Symbol const*)':
oslcomp.cpp:(.text+0x6594): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
oslcomp.cpp:(.text+0x6785): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/osl/lib/liboslcomp.a(oslcomp.cpp.o): In function `OSL_v1_11::pvt::OSLCompilerImpl::write_oso_file(OpenImageIO_v2_1::string_view, OpenImageIO_v2_1::string_view)':
oslcomp.cpp:(.text+0x6fe5): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
oslcomp.cpp:(.text+0x71d1): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/osl/lib/liboslcomp.a(oslcomp.cpp.o):oslcomp.cpp:(.text+0x73ac): more undefined references to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libclangFrontend.a(CompilerInstance.cpp.o): In function `std::_Sp_counted_ptr_inplace<llvm::sys::fs::detail::DirIterState, std::allocator<llvm::sys::fs::detail::DirIterState>, (__gnu_cxx::_Lock_policy)2>::_M_get_deleter(std::type_info const&)':
CompilerInstance.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN4llvm3sys2fs6detail12DirIterStateESaIS4_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info[_ZNSt23_Sp_counted_ptr_inplaceIN4llvm3sys2fs6detail12DirIterStateESaIS4_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info]+0x13): undefined reference to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)'
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libclangFrontend.a(CompilerInstance.cpp.o): In function `std::_Sp_counted_ptr_inplace<clang::GlobalCodeCompletionAllocator, std::allocator<clang::GlobalCodeCompletionAllocator>, (__gnu_cxx::_Lock_policy)2>::_M_get_deleter(std::type_info const&)':
CompilerInstance.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN5clang29GlobalCodeCompletionAllocatorESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info[_ZNSt23_Sp_counted_ptr_inplaceIN5clang29GlobalCodeCompletionAllocatorESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info]+0x13): undefined reference to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)'
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libclangFrontend.a(CompilerInstance.cpp.o): In function `std::_Sp_counted_ptr_inplace<clang::Preprocessor, std::allocator<clang::Preprocessor>, (__gnu_cxx::_Lock_policy)2>::_M_get_deleter(std::type_info const&)':
CompilerInstance.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN5clang12PreprocessorESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info[_ZNSt23_Sp_counted_ptr_inplaceIN5clang12PreprocessorESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info]+0x13): undefined reference to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)'
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libclangFrontend.a(CompilerInstance.cpp.o): In function `std::_Sp_counted_ptr_inplace<clang::DependencyFileGenerator, std::allocator<clang::DependencyFileGenerator>, (__gnu_cxx::_Lock_policy)2>::_M_get_deleter(std::type_info const&)':
CompilerInstance.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN5clang23DependencyFileGeneratorESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info[_ZNSt23_Sp_counted_ptr_inplaceIN5clang23DependencyFileGeneratorESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info]+0x13): undefined reference to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)'
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libclangFrontend.a(CompilerInstance.cpp.o): In function `std::_Sp_counted_ptr_inplace<clang::ModuleDependencyCollector, std::allocator<clang::ModuleDependencyCollector>, (__gnu_cxx::_Lock_policy)2>::_M_get_deleter(std::type_info const&)':
CompilerInstance.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN5clang25ModuleDependencyCollectorESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info[_ZNSt23_Sp_counted_ptr_inplaceIN5clang25ModuleDependencyCollectorESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info]+0x13): undefined reference to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)'
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libclangFrontend.a(CompilerInstance.cpp.o):CompilerInstance.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN5clang18CompilerInvocationESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info[_ZNSt23_Sp_counted_ptr_inplaceIN5clang18CompilerInvocationESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info]+0x13): more undefined references to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)' follow
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(TimeSampling.cpp.o): In function `Alembic::AbcCoreAbstract::v12::TimeSampling::init()':
TimeSampling.cpp:(.text+0x1c5): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
TimeSampling.cpp:(.text+0x56e): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(TimeSampling.cpp.o): In function `Alembic::AbcCoreAbstract::v12::TimeSampling::getSampleTime(long) const':
TimeSampling.cpp:(.text+0xa97): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(TimeSampling.cpp.o): In function `Alembic::AbcCoreAbstract::v12::TimeSamplingType::TimeSamplingType(double)':
TimeSampling.cpp:(.text._ZN7Alembic15AbcCoreAbstract3v1216TimeSamplingTypeC2Ed[_ZN7Alembic15AbcCoreAbstract3v1216TimeSamplingTypeC5Ed]+0x53): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(ArraySample.cpp.o): In function `Alembic::AbcCoreAbstract::v12::ArraySample::getKey() const':
ArraySample.cpp:(.text+0x2bb): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(ErrorHandler.cpp.o):ErrorHandler.cpp:(.text+0x116): more undefined references to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(OCurves.cpp.o): In function `Alembic::AbcGeom::v12::OTypedGeomParam<Alembic::Abc::v12::Float32TPTraits>::OTypedGeomParam(std::shared_ptr<Alembic::AbcCoreAbstract::v12::CompoundPropertyWriter>, std::string const&, bool, Alembic::AbcGeom::v12::GeometryScope, unsigned long, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&)':
OCurves.cpp:(.text._ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1215Float32TPTraitsEEC2ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_[_ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1215Float32TPTraitsEEC5ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_]+0x31a): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
OCurves.cpp:(.text._ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1215Float32TPTraitsEEC2ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_[_ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1215Float32TPTraitsEEC5ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_]+0x394): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(OCurves.cpp.o): In function `Alembic::AbcGeom::v12::OTypedGeomParam<Alembic::Abc::v12::N3fTPTraits>::OTypedGeomParam(std::shared_ptr<Alembic::AbcCoreAbstract::v12::CompoundPropertyWriter>, std::string const&, bool, Alembic::AbcGeom::v12::GeometryScope, unsigned long, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&)':
OCurves.cpp:(.text._ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1211N3fTPTraitsEEC2ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_[_ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1211N3fTPTraitsEEC5ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_]+0x31a): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
OCurves.cpp:(.text._ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1211N3fTPTraitsEEC2ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_[_ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1211N3fTPTraitsEEC5ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_]+0x394): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(OCurves.cpp.o): In function `Alembic::Abc::v12::OTypedArrayProperty<Alembic::Abc::v12::P3fTPTraits>::init(std::shared_ptr<Alembic::AbcCoreAbstract::v12::CompoundPropertyWriter>, std::string const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&)':
OCurves.cpp:(.text._ZN7Alembic3Abc3v1219OTypedArrayPropertyINS1_11P3fTPTraitsEE4initESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsRKNS1_8ArgumentESE_SE_SE_[_ZN7Alembic3Abc3v1219OTypedArrayPropertyINS1_11P3fTPTraitsEE4initESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsRKNS1_8ArgumentESE_SE_SE_]+0x393): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(OCurves.cpp.o): In function `Alembic::AbcGeom::v12::OTypedGeomParam<Alembic::Abc::v12::V2fTPTraits>::OTypedGeomParam(std::shared_ptr<Alembic::AbcCoreAbstract::v12::CompoundPropertyWriter>, std::string const&, bool, Alembic::AbcGeom::v12::GeometryScope, unsigned long, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&)':
OCurves.cpp:(.text._ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1211V2fTPTraitsEEC2ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_[_ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1211V2fTPTraitsEEC5ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_]+0x31a): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
OCurves.cpp:(.text._ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1211V2fTPTraitsEEC2ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_[_ZN7Alembic7AbcGeom3v1215OTypedGeomParamINS_3Abc3v1211V2fTPTraitsEEC5ESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsbNS1_13GeometryScopeEmRKNS4_8ArgumentESH_SH_]+0x394): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(OFaceSet.cpp.o): In function `Alembic::AbcGeom::v12::computeBoundsFromPositionsByFaces(Alembic::Abc::v12::TypedArraySample<Alembic::Abc::v12::Int32TPTraits> const&, Alembic::Abc::v12::TypedArraySample<Alembic::Abc::v12::Int32TPTraits> const&, Alembic::Abc::v12::TypedArraySample<Alembic::Abc::v12::Int32TPTraits> const&, Alembic::Abc::v12::TypedArraySample<Alembic::Abc::v12::P3fTPTraits> const&)':
OFaceSet.cpp:(.text+0x3245): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(OFaceSet.cpp.o): In function `Alembic::Abc::v12::OSchema<Alembic::AbcGeom::v12::FaceSetSchemaInfo>::init(std::shared_ptr<Alembic::AbcCoreAbstract::v12::CompoundPropertyWriter>, std::string const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&)':
OFaceSet.cpp:(.text._ZN7Alembic3Abc3v127OSchemaINS_7AbcGeom3v1217FaceSetSchemaInfoEE4initESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsRKNS1_8ArgumentESG_SG_SG_[_ZN7Alembic3Abc3v127OSchemaINS_7AbcGeom3v1217FaceSetSchemaInfoEE4initESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsRKNS1_8ArgumentESG_SG_SG_]+0x10a5): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(OFaceSet.cpp.o): In function `Alembic::Abc::v12::OTypedScalarProperty<Alembic::Abc::v12::Uint32TPTraits>::init(std::shared_ptr<Alembic::AbcCoreAbstract::v12::CompoundPropertyWriter>, std::string const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&)':
OFaceSet.cpp:(.text._ZN7Alembic3Abc3v1220OTypedScalarPropertyINS1_14Uint32TPTraitsEE4initESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsRKNS1_8ArgumentESE_SE_SE_[_ZN7Alembic3Abc3v1220OTypedScalarPropertyINS1_14Uint32TPTraitsEE4initESt10shared_ptrINS_15AbcCoreAbstract3v1222CompoundPropertyWriterEERKSsRKNS1_8ArgumentESE_SE_SE_]+0x1139): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(IFaceSet.cpp.o): In function `Alembic::Abc::v12::ITypedScalarProperty<Alembic::Abc::v12::Uint32TPTraits>::ITypedScalarProperty(Alembic::Abc::v12::ICompoundProperty const&, std::string const&, Alembic::Abc::v12::Argument const&, Alembic::Abc::v12::Argument const&)':
IFaceSet.cpp:(.text._ZN7Alembic3Abc3v1220ITypedScalarPropertyINS1_14Uint32TPTraitsEEC2ERKNS1_17ICompoundPropertyERKSsRKNS1_8ArgumentESC_[_ZN7Alembic3Abc3v1220ITypedScalarPropertyINS1_14Uint32TPTraitsEEC5ERKNS1_17ICompoundPropertyERKSsRKNS1_8ArgumentESC_]+0x113f): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
IFaceSet.cpp:(.text._ZN7Alembic3Abc3v1220ITypedScalarPropertyINS1_14Uint32TPTraitsEEC2ERKNS1_17ICompoundPropertyERKSsRKNS1_8ArgumentESC_[_ZN7Alembic3Abc3v1220ITypedScalarPropertyINS1_14Uint32TPTraitsEEC5ERKNS1_17ICompoundPropertyERKSsRKNS1_8ArgumentESC_]+0x11e3): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/alembic/lib/libAlembic.a(ONuPatch.cpp.o):ONuPatch.cpp:(.text+0x6909): more undefined references to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(proxyTypes.cpp.o): In function `usdBlender__pxrReserved__::Sdf_ListEditor<usdBlender__pxrReserved__::SdfNameTokenKeyPolicy>::_ValidateEdit(usdBlender__pxrReserved__::SdfListOpType, std::vector<usdBlender__pxrReserved__::TfToken, std::allocator<usdBlender__pxrReserved__::TfToken> > const&, std::vector<usdBlender__pxrReserved__::TfToken, std::allocator<usdBlender__pxrReserved__::TfToken> > const&) const':
proxyTypes.cpp:(.text._ZNK25usdBlender__pxrReserved__14Sdf_ListEditorINS_21SdfNameTokenKeyPolicyEE13_ValidateEditENS_13SdfListOpTypeERKSt6vectorINS_7TfTokenESaIS5_EES9_[_ZNK25usdBlender__pxrReserved__14Sdf_ListEditorINS_21SdfNameTokenKeyPolicyEE13_ValidateEditENS_13SdfListOpTypeERKSt6vectorINS_7TfTokenESaIS5_EES9_]+0xf5): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(proxyTypes.cpp.o): In function `usdBlender__pxrReserved__::Sdf_ListEditor<usdBlender__pxrReserved__::SdfPayloadTypePolicy>::_ValidateEdit(usdBlender__pxrReserved__::SdfListOpType, std::vector<usdBlender__pxrReserved__::SdfPayload, std::allocator<usdBlender__pxrReserved__::SdfPayload> > const&, std::vector<usdBlender__pxrReserved__::SdfPayload, std::allocator<usdBlender__pxrReserved__::SdfPayload> > const&) const':
proxyTypes.cpp:(.text._ZNK25usdBlender__pxrReserved__14Sdf_ListEditorINS_20SdfPayloadTypePolicyEE13_ValidateEditENS_13SdfListOpTypeERKSt6vectorINS_10SdfPayloadESaIS5_EES9_[_ZNK25usdBlender__pxrReserved__14Sdf_ListEditorINS_20SdfPayloadTypePolicyEE13_ValidateEditENS_13SdfListOpTypeERKSt6vectorINS_10SdfPayloadESaIS5_EES9_]+0xe6): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(proxyTypes.cpp.o): In function `usdBlender__pxrReserved__::Sdf_ListEditor<usdBlender__pxrReserved__::SdfReferenceTypePolicy>::_ValidateEdit(usdBlender__pxrReserved__::SdfListOpType, std::vector<usdBlender__pxrReserved__::SdfReference, std::allocator<usdBlender__pxrReserved__::SdfReference> > const&, std::vector<usdBlender__pxrReserved__::SdfReference, std::allocator<usdBlender__pxrReserved__::SdfReference> > const&) const':
proxyTypes.cpp:(.text._ZNK25usdBlender__pxrReserved__14Sdf_ListEditorINS_22SdfReferenceTypePolicyEE13_ValidateEditENS_13SdfListOpTypeERKSt6vectorINS_12SdfReferenceESaIS5_EES9_[_ZNK25usdBlender__pxrReserved__14Sdf_ListEditorINS_22SdfReferenceTypePolicyEE13_ValidateEditENS_13SdfListOpTypeERKSt6vectorINS_12SdfReferenceESaIS5_EES9_]+0xe6): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(textFileFormat.cpp.o): In function `usdBlender__pxrReserved__::_WriteLayer(usdBlender__pxrReserved__::SdfLayer const*, usdBlender__pxrReserved__::Sdf_TextOutput&, std::string const&, std::string const&, std::string const&)':
textFileFormat.cpp:(.text+0xb060): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(changes.cpp.o): In function `usdBlender__pxrReserved__::PcpChanges::DidChange(usdBlender__pxrReserved__::TfSpan<usdBlender__pxrReserved__::PcpCache const*> const&, std::vector<std::pair<usdBlender__pxrReserved__::TfWeakPtr<usdBlender__pxrReserved__::SdfLayer>, usdBlender__pxrReserved__::SdfChangeList>, std::allocator<std::pair<usdBlender__pxrReserved__::TfWeakPtr<usdBlender__pxrReserved__::SdfLayer>, usdBlender__pxrReserved__::SdfChangeList> > > const&)':
changes.cpp:(.text+0x55f6): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
changes.cpp:(.text+0x5c12): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(changes.cpp.o): In function `std::enable_if<!std::is_enum<usdBlender__pxrReserved__::TfWeakPtr<usdBlender__pxrReserved__::PcpLayerStack> >::value, std::string>::type usdBlender__pxrReserved__::TfStringify<usdBlender__pxrReserved__::TfWeakPtr<usdBlender__pxrReserved__::PcpLayerStack> >(usdBlender__pxrReserved__::TfWeakPtr<usdBlender__pxrReserved__::PcpLayerStack> const&)':
changes.cpp:(.text._ZN25usdBlender__pxrReserved__11TfStringifyINS_9TfWeakPtrINS_13PcpLayerStackEEEEENSt9enable_ifIXntsrSt7is_enumIT_E5valueESsE4typeERKS6_[_ZN25usdBlender__pxrReserved__11TfStringifyINS_9TfWeakPtrINS_13PcpLayerStackEEEEENSt9enable_ifIXntsrSt7is_enumIT_E5valueESsE4typeERKS6_]+0x1b): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(clipSetDefinition.cpp.o): In function `usdBlender__pxrReserved__::_DeriveClipInfo(std::string const&, double, double, double, double, boost::optional<usdBlender__pxrReserved__::VtArray<usdBlender__pxrReserved__::GfVec2d> >*, boost::optional<usdBlender__pxrReserved__::VtArray<usdBlender__pxrReserved__::GfVec2d> >*, boost::optional<usdBlender__pxrReserved__::VtArray<usdBlender__pxrReserved__::SdfAssetPath> >*, usdBlender__pxrReserved__::SdfPath const&, usdBlender__pxrReserved__::TfWeakPtr<usdBlender__pxrReserved__::PcpLayerStack> const&, unsigned long)':
clipSetDefinition.cpp:(.text+0x1a14): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(instanceCache.cpp.o): In function `usdBlender__pxrReserved__::Usd_InstanceCache::_CreateOrUpdatePrototypeForInstances(usdBlender__pxrReserved__::Usd_InstanceKey const&, std::vector<usdBlender__pxrReserved__::SdfPath, std::allocator<usdBlender__pxrReserved__::SdfPath> >*, usdBlender__pxrReserved__::Usd_InstanceChanges*, std::unordered_map<usdBlender__pxrReserved__::SdfPath, usdBlender__pxrReserved__::SdfPath, usdBlender__pxrReserved__::SdfPath::Hash, std::equal_to<usdBlender__pxrReserved__::SdfPath>, std::allocator<std::pair<usdBlender__pxrReserved__::SdfPath const, usdBlender__pxrReserved__::SdfPath> > > const&)':
instanceCache.cpp:(.text+0x4bb9): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/usd/lib/libusd_m.a(flattenUtils.cpp.o):flattenUtils.cpp:(.text+0x5c5e): more undefined references to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_parse<wchar_t>::do_real_get<long double>(std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, std::_Ios_Iostate&, long double&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getIeEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getIeEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_parse<wchar_t>::do_real_get<double>(std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, std::_Ios_Iostate&, double&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getIdEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getIdEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_parse<wchar_t>::do_real_get<float>(std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, std::_Ios_Iostate&, float&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getIfEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getIfEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_parse<char>::do_real_get<long double>(std::istreambuf_iterator<char, std::char_traits<char> >, std::istreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, std::_Ios_Iostate&, long double&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getIeEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getIeEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_parse<char>::do_real_get<double>(std::istreambuf_iterator<char, std::char_traits<char> >, std::istreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, std::_Ios_Iostate&, double&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getIdEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getIdEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o):numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getIfEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getIfEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): more undefined references to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_format<wchar_t>::do_real_put<long double>(std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, wchar_t, long double) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIwE11do_real_putIeEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_[_ZNK5boost6locale4util15base_num_formatIwE11do_real_putIeEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_]+0x1a2): undefined reference to `std::basic_ostringstream<wchar_t, std::char_traits<wchar_t>, std::allocator<wchar_t> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_format<wchar_t>::do_real_put<double>(std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, wchar_t, double) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIwE11do_real_putIdEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_[_ZNK5boost6locale4util15base_num_formatIwE11do_real_putIdEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_]+0x182): undefined reference to `std::basic_ostringstream<wchar_t, std::char_traits<wchar_t>, std::allocator<wchar_t> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_format<char>::do_real_put<long double>(std::ostreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, char, long double) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIcE11do_real_putIeEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_[_ZNK5boost6locale4util15base_num_formatIcE11do_real_putIeEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_]+0x1b2): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_format<char>::do_real_put<double>(std::ostreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, char, double) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIcE11do_real_putIdEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_[_ZNK5boost6locale4util15base_num_formatIcE11do_real_putIdEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_]+0x182): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_format<wchar_t>::do_real_put<unsigned long long>(std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, wchar_t, unsigned long long) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIwE11do_real_putIyEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_[_ZNK5boost6locale4util15base_num_formatIwE11do_real_putIyEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_]+0x192): undefined reference to `std::basic_ostringstream<wchar_t, std::char_traits<wchar_t>, std::allocator<wchar_t> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_format<wchar_t>::do_real_put<long long>(std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, wchar_t, long long) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIwE11do_real_putIxEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_[_ZNK5boost6locale4util15base_num_formatIwE11do_real_putIxEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_]+0x192): undefined reference to `std::basic_ostringstream<wchar_t, std::char_traits<wchar_t>, std::allocator<wchar_t> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_format<wchar_t>::do_real_put<unsigned long>(std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, wchar_t, unsigned long) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIwE11do_real_putImEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_[_ZNK5boost6locale4util15base_num_formatIwE11do_real_putImEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_]+0x192): undefined reference to `std::basic_ostringstream<wchar_t, std::char_traits<wchar_t>, std::allocator<wchar_t> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_format<wchar_t>::do_real_put<long>(std::ostreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, wchar_t, long) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIwE11do_real_putIlEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_[_ZNK5boost6locale4util15base_num_formatIwE11do_real_putIlEESt19ostreambuf_iteratorIwSt11char_traitsIwEES8_RSt8ios_basewT_]+0x192): undefined reference to `std::basic_ostringstream<wchar_t, std::char_traits<wchar_t>, std::allocator<wchar_t> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_parse<wchar_t>::do_real_get<unsigned long long>(std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, std::_Ios_Iostate&, unsigned long long&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getIyEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getIyEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_parse<wchar_t>::do_real_get<long long>(std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, std::_Ios_Iostate&, long long&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getIxEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getIxEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_parse<wchar_t>::do_real_get<unsigned long>(std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, std::_Ios_Iostate&, unsigned long&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getImEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getImEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_parse<wchar_t>::do_real_get<unsigned int>(std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, std::_Ios_Iostate&, unsigned int&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getIjEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getIjEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> > boost::locale::util::base_num_parse<wchar_t>::do_real_get<unsigned short>(std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::istreambuf_iterator<wchar_t, std::char_traits<wchar_t> >, std::ios_base&, std::_Ios_Iostate&, unsigned short&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getItEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getItEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o):numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIwE11do_real_getIlEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIwE11do_real_getIlEESt19istreambuf_iteratorIwSt11char_traitsIwEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): more undefined references to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_format<char>::do_real_put<unsigned long long>(std::ostreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, char, unsigned long long) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIcE11do_real_putIyEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_[_ZNK5boost6locale4util15base_num_formatIcE11do_real_putIyEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_]+0x192): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_format<char>::do_real_put<long long>(std::ostreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, char, long long) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIcE11do_real_putIxEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_[_ZNK5boost6locale4util15base_num_formatIcE11do_real_putIxEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_]+0x172): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_format<char>::do_real_put<unsigned long>(std::ostreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, char, unsigned long) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIcE11do_real_putImEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_[_ZNK5boost6locale4util15base_num_formatIcE11do_real_putImEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_]+0x192): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::ostreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_format<char>::do_real_put<long>(std::ostreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, char, long) const':
numeric.cpp:(.text._ZNK5boost6locale4util15base_num_formatIcE11do_real_putIlEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_[_ZNK5boost6locale4util15base_num_formatIcE11do_real_putIlEESt19ostreambuf_iteratorIcSt11char_traitsIcEES8_RSt8ios_basecT_]+0x172): undefined reference to `std::basic_ostringstream<char, std::char_traits<char>, std::allocator<char> >::basic_ostringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_parse<char>::do_real_get<unsigned long long>(std::istreambuf_iterator<char, std::char_traits<char> >, std::istreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, std::_Ios_Iostate&, unsigned long long&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getIyEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getIyEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_parse<char>::do_real_get<long long>(std::istreambuf_iterator<char, std::char_traits<char> >, std::istreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, std::_Ios_Iostate&, long long&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getIxEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getIxEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_parse<char>::do_real_get<unsigned long>(std::istreambuf_iterator<char, std::char_traits<char> >, std::istreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, std::_Ios_Iostate&, unsigned long&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getImEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getImEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_parse<char>::do_real_get<unsigned int>(std::istreambuf_iterator<char, std::char_traits<char> >, std::istreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, std::_Ios_Iostate&, unsigned int&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getIjEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getIjEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o): In function `std::istreambuf_iterator<char, std::char_traits<char> > boost::locale::util::base_num_parse<char>::do_real_get<unsigned short>(std::istreambuf_iterator<char, std::char_traits<char> >, std::istreambuf_iterator<char, std::char_traits<char> >, std::ios_base&, std::_Ios_Iostate&, unsigned short&) const':
numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getItEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getItEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): undefined reference to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()'
/tmp/blender-git/lib/linux_centos7_x86_64/boost/lib/libboost_locale.a(numeric.o):numeric.cpp:(.text._ZNK5boost6locale4util14base_num_parseIcE11do_real_getIlEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_[_ZNK5boost6locale4util14base_num_parseIcE11do_real_getIlEESt19istreambuf_iteratorIcSt11char_traitsIcEES8_S8_RSt8ios_baseRSt12_Ios_IostateRT_]+0xaa): more undefined references to `std::basic_stringstream<char, std::char_traits<char>, std::allocator<char> >::basic_stringstream()' follow
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libLLVMMCJIT.a(MCJIT.cpp.o): In function `std::_Sp_counted_ptr_inplace<llvm::SectionMemoryManager, std::allocator<llvm::SectionMemoryManager>, (__gnu_cxx::_Lock_policy)2>::_M_get_deleter(std::type_info const&)':
MCJIT.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN4llvm20SectionMemoryManagerESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info[_ZNSt23_Sp_counted_ptr_inplaceIN4llvm20SectionMemoryManagerESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info]+0x13): undefined reference to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)'
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libLLVMSupport.a(BinaryStreamRef.cpp.o): In function `std::_Sp_counted_ptr_inplace<(anonymous namespace)::ArrayRefImpl, std::allocator<(anonymous namespace)::ArrayRefImpl>, (__gnu_cxx::_Lock_policy)2>::_M_get_deleter(std::type_info const&)':
BinaryStreamRef.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN12_GLOBAL__N_112ArrayRefImplESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info+0x13): undefined reference to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)'
/tmp/blender-git/lib/linux_centos7_x86_64/llvm/lib/libLLVMSupport.a(BinaryStreamRef.cpp.o): In function `std::_Sp_counted_ptr_inplace<(anonymous namespace)::MutableArrayRefImpl, std::allocator<(anonymous namespace)::MutableArrayRefImpl>, (__gnu_cxx::_Lock_policy)2>::_M_get_deleter(std::type_info const&)':
BinaryStreamRef.cpp:(.text._ZNSt23_Sp_counted_ptr_inplaceIN12_GLOBAL__N_119MutableArrayRefImplESaIS1_ELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info+0x13): undefined reference to `std::_Sp_make_shared_tag::_S_eq(std::type_info const&)'
clang: error: linker command failed with exit code 1 (use -v to see invocation)
source/creator/CMakeFiles/blender.dir/build.make:580: recipe for target 'bin/blender' failed
make[3]: *** [bin/blender] Error 1
CMakeFiles/Makefile2:8862: recipe for target 'source/creator/CMakeFiles/blender.dir/all' failed
make[2]: *** [source/creator/CMakeFiles/blender.dir/all] Error 2
Makefile:162: recipe for target 'all' failed
make[1]: *** [all] Error 2
GNUmakefile:340: recipe for target 'all' failed
make: *** [all] Error 2
```
https://wiki.blender.org/wiki/Building_Blender/Linux/Ubuntu#Automatic_Dependency_Installation
```
cd ~/blender-git
./blender/build_files/build_environment/install_deps.sh
```
```
Forced Boost building, as requested...
Building Boost-1.73.0
Ensuring /opt/lib exists and is writable by us
Downloading Boost-1.73.0
--2021-07-09 00:57:45--  https://dl.bintray.com/boostorg/release/1.73.0/source/boost_1_73_0.tar.bz2
Resolving dl.bintray.com (dl.bintray.com)... 3.124.176.138, 35.157.24.53
Connecting to dl.bintray.com (dl.bintray.com)|3.124.176.138|:443... connected.
HTTP request sent, awaiting response... 403 Forbidden
2021-07-09 00:57:45 ERROR 403: Forbidden.

ERROR! wget could not find https://dl.bintray.com/boostorg/release/1.73.0/source/boost_1_73_0.tar.bz2, or could not write it to /home/constantine/src/blender-deps/boost-1.73.0.tar.bz2, exiting
```
https://www.boost.org/users/history/version_1_73_0.html
```
rm /home/constantine/src/blender-deps/boost-1.73.0.tar.bz2 
wget https://boostorg.jfrog.io/artifactory/main/release/1.73.0/source/boost_1_73_0.tar.bz2
mv boost_1_73_0.tar.bz2 /home/constantine/src/blender-deps/
```
```diff
diff --git a/build_files/build_environment/install_deps.sh b/build_files/build_environment/install_deps.sh
index 7cd21b2..d589d8f 100755
--- a/build_files/build_environment/install_deps.sh
+++ b/build_files/build_environment/install_deps.sh
@@ -1019,7 +1019,7 @@ PRINT ""
 PYTHON_SOURCE=( "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tgz" )
 
 _boost_version_nodots=`echo "$BOOST_VERSION" | sed -r 's/\./_/g'`
-BOOST_SOURCE=( "https://dl.bintray.com/boostorg/release/$BOOST_VERSION/source/boost_$_boost_version_nodots.tar.bz2" )
+BOOST_SOURCE=( "https://boostorg.jfrog.io/artifactory/main/release/$BOOST_VERSION/source/boost_$_boost_version_nodots.tar.bz2" )
 BOOST_BUILD_MODULES="--with-system --with-filesystem --with-thread --with-regex --with-locale --with-date_time --with-wave --with-iostreams --with-python --with-program_options --with-serialization --with-atomic"
 
 TBB_SOURCE=( "https://github.com/oneapi-src/oneTBB/archive/$TBB_VERSION$TBB_VERSION_UPDATE.tar.gz" )
```
```
Unpacking OpenColorIO-2.0.0
CMake Error at CMakeLists.txt:8 (cmake_minimum_required):
  CMake 3.12 or higher is required.  You are running version 3.10.2


-- Configuring incomplete, errors occurred!
make: *** No targets specified and no makefile found.  Stop.
make: *** No rule to make target 'clean'.  Stop.
ERROR! OpenColorIO-2.0.0 failed to compile, exiting
```
https://packages.ubuntu.com/focal/amd64/cmake/download

https://mirrors.kernel.org/ubuntu/pool/main/c/cmake/cmake_3.16.3-1ubuntu1_amd64.deb
```
$ sudo dpkg -i cmake_3.16.3-1ubuntu1_amd64.deb 
Selecting previously unselected package cmake.
(Reading database ... 176089 files and directories currently installed.)
Preparing to unpack cmake_3.16.3-1ubuntu1_amd64.deb ...
Unpacking cmake (3.16.3-1ubuntu1) ...
dpkg: dependency problems prevent configuration of cmake:
 cmake depends on cmake-data (= 3.16.3-1ubuntu1); however:
  Version of cmake-data on system is 3.10.2-1ubuntu2.18.04.1.
 cmake depends on libarchive13 (>= 3.3.3); however:
  Version of libarchive13:amd64 on system is 3.2.2-3.1ubuntu0.6.
 cmake depends on libgcc-s1 (>= 3.0); however:
  Package libgcc-s1 is not installed.
 cmake depends on libstdc++6 (>= 9); however:
  Version of libstdc++6:amd64 on system is 8.4.0-1ubuntu1~18.04.

dpkg: error processing package cmake (--install):
 dependency problems - leaving unconfigured
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Errors were encountered while processing:
 cmake
```
```
[ 34%] Building CXX object src/OpenColorIO/CMakeFiles/OpenColorIO.dir/OCIOYaml.cpp.o
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::load(const YAML::Node&, bool&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:46:36: error: 'const class YAML::Node' has no member named 'Mark'
          os << "At line " << (node.Mark().line + 1)
                                    ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::load(const YAML::Node&, int&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:62:35: error: 'const class YAML::Node' has no member named 'Mark'
         os << "At line " << (node.Mark().line + 1)
                                   ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::load(const YAML::Node&, float&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:78:35: error: 'const class YAML::Node' has no member named 'Mark'
         os << "At line " << (node.Mark().line + 1)
                                   ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::load(const YAML::Node&, double&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:94:35: error: 'const class YAML::Node' has no member named 'Mark'
         os << "At line " << (node.Mark().line + 1)
                                   ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::load(const YAML::Node&, std::__cxx11::string&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:110:35: error: 'const class YAML::Node' has no member named 'Mark'
         os << "At line " << (node.Mark().line + 1)
                                   ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::load(const YAML::Node&, StringUtils::StringVec&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:126:35: error: 'const class YAML::Node' has no member named 'Mark'
         os << "At line " << (node.Mark().line + 1)
                                   ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::load(const YAML::Node&, std::vector<float>&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:142:35: error: 'const class YAML::Node' has no member named 'Mark'
         os << "At line " << (node.Mark().line + 1)
                                   ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::load(const YAML::Node&, std::vector<double>&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:158:35: error: 'const class YAML::Node' has no member named 'Mark'
         os << "At line " << (node.Mark().line + 1)
                                   ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::LogUnknownKeyWarning(const YAML::Node&, const YAML::Node&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:272:30: error: 'const class YAML::Node' has no member named 'Mark'
     os << "At line " << (key.Mark().line + 1)
                              ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::throwError(const YAML::Node&, const string&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:293:31: error: 'const class YAML::Node' has no member named 'Mark'
     os << "At line " << (node.Mark().line + 1)
                               ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::throwValueError(const string&, const YAML::Node&, const string&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:308:30: error: 'const class YAML::Node' has no member named 'Mark'
     os << "At line " << (key.Mark().line + 1)
                              ^~~~
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp: In function 'void OpenColorIO_v2_0::{anonymous}::throwValueError(const YAML::Node&, const string&)':
/home/constantine/src/blender-deps/OpenColorIO-2.0.0/src/OpenColorIO/OCIOYaml.cpp:322:30: error: 'const class YAML::Node' has no member named 'Mark'
     os << "At line " << (key.Mark().line + 1)
                              ^~~~
[ 34%] Building CXX object src/OpenColorIO/CMakeFiles/OpenColorIO.dir/Op.cpp.o
src/OpenColorIO/CMakeFiles/OpenColorIO.dir/build.make:1027: recipe for target 'src/OpenColorIO/CMakeFiles/OpenColorIO.dir/OCIOYaml.cpp.o' failed
make[2]: *** [src/OpenColorIO/CMakeFiles/OpenColorIO.dir/OCIOYaml.cpp.o] Error 1
make[2]: *** Waiting for unfinished jobs....
CMakeFiles/Makefile2:482: recipe for target 'src/OpenColorIO/CMakeFiles/OpenColorIO.dir/all' failed
make[1]: *** [src/OpenColorIO/CMakeFiles/OpenColorIO.dir/all] Error 2
Makefile:145: recipe for target 'all' failed
make: *** [all] Error 2
ERROR! OpenColorIO-2.0.0 failed to compile, exiting
```
NOTE: OpenColorIO replaces its folder on compile command run, try to patch `OCIOYaml.cpp` in time.
```diff
diff --git a/src/OpenColorIO/OCIOYaml.cpp b/src/OpenColorIO/OCIOYaml.cpp
index 2cf64df..5f0ca66 100644
--- a/src/OpenColorIO/OCIOYaml.cpp
+++ b/src/OpenColorIO/OCIOYaml.cpp
@@ -43,7 +43,7 @@ inline void load(const YAML::Node& node, bool& x)
     catch (const std::exception & e)
     {
         std::ostringstream os;
-         os << "At line " << (node.Mark().line + 1)
+         os << "At line " << (0)
             << ", '" << node.Tag() << "' parsing boolean failed "
             << "with: " << e.what();
         throw Exception(os.str().c_str());
@@ -59,7 +59,7 @@ inline void load(const YAML::Node& node, int& x)
     catch (const std::exception & e)
     {
         std::ostringstream os;
-        os << "At line " << (node.Mark().line + 1)
+        os << "At line " << (0)
             << ", '" << node.Tag() << "' parsing integer failed "
             << "with: " << e.what();
         throw Exception(os.str().c_str());
@@ -75,7 +75,7 @@ inline void load(const YAML::Node& node, float& x)
     catch (const std::exception & e)
     {
         std::ostringstream os;
-        os << "At line " << (node.Mark().line + 1)
+        os << "At line " << (0)
             << ", '" << node.Tag() << "' parsing float failed "
             << "with: " << e.what();
         throw Exception(os.str().c_str());
@@ -91,7 +91,7 @@ inline void load(const YAML::Node& node, double& x)
     catch (const std::exception & e)
     {
         std::ostringstream os;
-        os << "At line " << (node.Mark().line + 1)
+        os << "At line " << (0)
             << ", '" << node.Tag() << "' parsing double failed "
             << "with: " << e.what();
         throw Exception(os.str().c_str());
@@ -107,7 +107,7 @@ inline void load(const YAML::Node& node, std::string& x)
     catch (const std::exception & e)
     {
         std::ostringstream os;
-        os << "At line " << (node.Mark().line + 1)
+        os << "At line " << (0)
             << ", '" << node.Tag() << "' parsing string failed "
             << "with: " << e.what();
         throw Exception(os.str().c_str());
@@ -123,7 +123,7 @@ inline void load(const YAML::Node & node, StringUtils::StringVec & x)
     catch (const std::exception & e)
     {
         std::ostringstream os;
-        os << "At line " << (node.Mark().line + 1)
+        os << "At line " << (0)
            << ", '" << node.Tag() << "' parsing StringVec failed "
            << "with: " << e.what();
         throw Exception(os.str().c_str());
@@ -139,7 +139,7 @@ inline void load(const YAML::Node & node, std::vector<float> & x)
     catch (const std::exception & e)
     {
         std::ostringstream os;
-        os << "At line " << (node.Mark().line + 1)
+        os << "At line " << (0)
            << ", '" << node.Tag() << "' parsing vector<float> failed "
            << "with: " << e.what();
         throw Exception(os.str().c_str());
@@ -155,7 +155,7 @@ inline void load(const YAML::Node& node, std::vector<double>& x)
     catch (const std::exception & e)
     {
         std::ostringstream os;
-        os << "At line " << (node.Mark().line + 1)
+        os << "At line " << (0)
            << ", '" << node.Tag() << "' parsing vector<double> failed "
            << "with: " << e.what();
         throw Exception(os.str().c_str());
@@ -269,7 +269,7 @@ inline void LogUnknownKeyWarning(const YAML::Node & node,
     load(key, keyName);
 
     std::ostringstream os;
-    os << "At line " << (key.Mark().line + 1)
+    os << "At line " << (0)
         << ", unknown key '" << keyName << "' in '" << node.Tag() << "'.";
 
     LogWarning(os.str());
@@ -290,7 +290,7 @@ inline void throwError(const YAML::Node & node,
                        const std::string & msg)
 {
     std::ostringstream os;
-    os << "At line " << (node.Mark().line + 1)
+    os << "At line " << (0)
         << ", '" << node.Tag() << "' parsing failed: " 
         << msg;
 
@@ -305,7 +305,7 @@ inline void throwValueError(const std::string & nodeName,
     load(key, keyName);
 
     std::ostringstream os;
-    os << "At line " << (key.Mark().line + 1)
+    os << "At line " << (0)
         << ", the value parsing of the key '" << keyName 
         << "' from '" << nodeName << "' failed: " << msg;
 
@@ -319,7 +319,7 @@ inline void throwValueError(const YAML::Node & key,
     load(key, keyName);
 
     std::ostringstream os;
-    os << "At line " << (key.Mark().line + 1)
+    os << "At line " << (0)
         << ", the value parsing of the key '" << keyName 
         << "' failed: " << msg;
 
```
```
Unpacking OpenShadingLanguage-1.11.10.0
ILMBASE_HOME=/opt/lib/openexr
-- The CXX compiler identification is GNU 7.5.0
-- The C compiler identification is GNU 7.5.0
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Check for working CXX compiler: /usr/bin/c++ - skipped
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Check for working C compiler: /usr/bin/cc - skipped
-- Detecting C compile features
-- Detecting C compile features - done
-- Building OSL 1.11.10.0
-- CMake version is 3.20.5
-- Configuring OSL 1.11.10.0
-- CMake 3.20.5
-- CMake system           = Linux-5.4.0-42-generic
-- CMake system name      = Linux
-- Project source dir     = /home/constantine/src/blender-deps/OpenShadingLanguage-1.11.10.0
-- Project build dir      = /home/constantine/src/blender-deps/OpenShadingLanguage-1.11.10.0/build
-- Project install prefix = /opt/lib/osl-1.11
-- Configuration types    = 
-- Build type             = Release
-- Setting Namespace to: OSL_v1_11
-- CMAKE_CXX_COMPILER     = /usr/bin/c++
-- CMAKE_CXX_COMPILER_ID  = GNU
-- Building for C++14
-- Compiling with SIMD level sse2
-- clang-format found: /usr/bin/clang-format
-- 
-- * Checking for dependencies...
-- *   - Missing a dependency 'Package'?
-- *     Try cmake -DPackage_ROOT=path or set environment var Package_ROOT=path
-- *     For many dependencies, we supply src/build-scripts/build_Package.bash
-- *   - To exclude an optional dependency (even if found),
-- *     -DUSE_Package=OFF or set environment var USE_Package=OFF 
-- 
-- CMAKE_PREFIX_PATH = /home/constantine/src/blender-deps/OpenShadingLanguage-1.11.10.0/ext/dist
-- Found Boost 107300 
-- Found ZLIB 1.2.11 
-- Could NOT find Imath (missing: Imath_DIR)
-- Could NOT find IlmBase (missing: IlmBase_DIR)
-- Could NOT find OpenEXR (missing: OpenEXR_DIR)
-- Found OpenEXR 2.2.0 
-- Found OpenImageIO 2.1.15.0 
-- Could NOT find pugixml (missing: pugixml_DIR)
-- Found pugixml 1.8 
-- LLVM 6.0.0 is outside the required range 7.0... 
-- LLVM library not found 
--     Try setting LLVM_ROOT ? 
--     Maybe this will help:  src/build-scripts/build_llvm.bash 
CMake Error at src/cmake/checked_find_package.cmake:148 (message):
  LLVM is required, aborting.
Call Stack (most recent call first):
  src/cmake/externalpackages.cmake:117 (checked_find_package)
  CMakeLists.txt:139 (include)


-- Configuring incomplete, errors occurred!
See also "/home/constantine/src/blender-deps/OpenShadingLanguage-1.11.10.0/build/CMakeFiles/CMakeOutput.log".
See also "/home/constantine/src/blender-deps/OpenShadingLanguage-1.11.10.0/build/CMakeFiles/CMakeError.log".
make: *** No targets specified and no makefile found.  Stop.
make: *** No rule to make target 'clean'.  Stop.
ERROR! OpenShadingLanguage-1.11.10.0 failed to compile, exiting
```
```
sudo apt install llvm-7-dev
LLVM_ROOT=/usr/lib/llvm-7 ./blender/build_files/build_environment/install_deps.sh
```
```
[ 14%] Building CXX object src/liboslcomp/CMakeFiles/oslcomp.dir/oslcomp.cpp.o
/home/constantine/src/blender-deps/OpenShadingLanguage-1.11.10.0/src/liboslcomp/oslcomp.cpp:24:10: fatal error: clang/Basic/TargetInfo.h: No such file or directory
 #include <clang/Basic/TargetInfo.h>
          ^~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
src/liboslcomp/CMakeFiles/oslcomp.dir/build.make:117: recipe for target 'src/liboslcomp/CMakeFiles/oslcomp.dir/oslcomp.cpp.o' failed
make[2]: *** [src/liboslcomp/CMakeFiles/oslcomp.dir/oslcomp.cpp.o] Error 1
CMakeFiles/Makefile2:296: recipe for target 'src/liboslcomp/CMakeFiles/oslcomp.dir/all' failed
make[1]: *** [src/liboslcomp/CMakeFiles/oslcomp.dir/all] Error 2
make[1]: *** Waiting for unfinished jobs....
[ 15%] Building CXX object src/liboslquery/CMakeFiles/oslquery.dir/osolex.cpp.o
[ 16%] Linking CXX shared library ../../lib/liboslquery.so
[ 16%] Built target oslquery
Makefile:155: recipe for target 'all' failed
make: *** [all] Error 2
ERROR! OpenShadingLanguage-1.11.10.0 failed to compile, exiting
```
```
sudo apt install libclang-7-dev
```
```
cp -Lr /opt/lib/ .
```
```
CMake Error at /usr/share/cmake-3.20/Modules/FindPackageHandleStandardArgs.cmake:230 (message):
  Could NOT find Embree (missing: _embree_LIBRARIES EMBREE_INCLUDE_DIR)
  (Required is at least version "3.8.0")
Call Stack (most recent call first):
  /usr/share/cmake-3.20/Modules/FindPackageHandleStandardArgs.cmake:594 (_FPHSA_FAILURE_MESSAGE)
  build_files/cmake/Modules/FindEmbree.cmake:82 (FIND_PACKAGE_HANDLE_STANDARD_ARGS)
  build_files/cmake/platform/platform_unix.cmake:406 (find_package)
  CMakeLists.txt:934 (include)


-- Configuring incomplete, errors occurred!
See also "/tmp/blender-git/build_linux/CMakeFiles/CMakeOutput.log".
See also "/tmp/blender-git/build_linux/CMakeFiles/CMakeError.log".
GNUmakefile:340: recipe for target 'all' failed
make: *** [all] Error 1
```
