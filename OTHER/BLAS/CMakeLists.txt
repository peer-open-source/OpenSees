add_library(BLAS OBJECT)

target_sources(BLAS
    PRIVATE
        dasum.f
        daxpy.f
        dcopy.f
        ddot.f
        dgbmv.f
        dgeev.f
        dgemm.f
        dgemv.f
        dger.f
        dnrm2.f
        dpotrf.f
        drot.f
        drotg.f
        dscal.f
        dswap.f
        dsymm.f
        dsymv.f
        dsyr2.f
        dsyr2k.f
        dsyr.f
        dsyrk.f
        dtbsv.f
        dtrmm.f
        dtrmv.f
        dtrsm.f
        dtrsv.f
        dtrtrs.f
        dzasum.f
        dznrm2.f
        icamax.f
        idamax.f
        isamax.f
        izamax.f
)

