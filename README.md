# [ICON Weather Model](https://www.icon-model.org/)
problematic af



# why was this so hard to find
need to install [icon model](https://gitlab.dkrz.de/icon/icon-model) into the repo, go to toplevel and:
```sh
git clone https://gitlab.dkrz.de/icon/icon-model
```

# dependency quick start guide
Before doing anything, ensure you have a [DKRZ](https://luv.dkrz.de/accounts/login/) account. It will require you to use your university email.

Done a few things so far, and putting here as I go along. Navigate to your `$HOME/.local` and clone and make (not install):
- [cdi](https://code.mpimet.mpg.de/attachments/9210)
- [lapack](https://github.com/Reference-LAPACK/lapack/archive/refs/tags/v3.12.0.tar.gz) - this comes with BLAS and I don't think it's a direct dependency of ICON. Also, I compiled with -flto for this, but obvs doesn't matter.
- **cant get a hold of the fortran-support package**
