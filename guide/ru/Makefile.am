figdir = figures
docname = gnucash-guide
lang = ru
omffile = $(docname)-ru.omf
entities = \
    ch_oview.xml \
    ch_basics.xml \
    ch_accts.xml \
    ch_txns.xml \
    ch_cbook.xml \
    ch_cc.xml \
    ch_expenses.xml \
    ch_loans.xml \
    ch_invest.xml \
    ch_reports.xml \
    ch_capgain.xml \
    ch_currency.xml \
    ch_dep.xml \
    ch_bus_features.xml \
    ch_budgets.xml \
    ch_oth_assets.xml \
    ch_python_bindings.xml \
    ch_import_business_data.xml \
    gnc-glossary.xml \
    fdl-appendix.xml \
    legal.xml \
    appendixa.xml \
    appendixb.xml \
    appendixc.xml \
    appendixd.xml
DISTCLEANFILES = $(docname)-C.omf.out
CLEANFILES = $(DISTCLEANFILES)
XSLTFLAGS_FO = --stringparam paper.type A4
include $(top_srcdir)/xmldocs.make
include $(top_srcdir)/pdf.make
include $(top_srcdir)/epub.make
if WITH_MOBI
include $(top_srcdir)/mobi.make
endif
