Stochastic Variational Inference (SVI)
======================================

We offer a brief overview of the three most commonly used ELBO implementations in NumPyro:

* `Trace_ELBO <https://num.pyro.ai/en/latest/svi.html#trace-elbo>`_ is our basic ELBO implementation.
* `TraceMeanField_ELBO <https://num.pyro.ai/en/latest/svi.html#tracemeanfield-elbo>`_ is like `Trace_ELBO` but computes part of the ELBO analytically if doing so is possible.
* `TraceGraph_ELBO <http://num.pyro.ai/en/latest/svi.html#tracegraph-elbo>`_ offers variance reduction strategies for models with discrete latent variables. Generally speaking, this ELBO should always be used for models with discrete latent variables.

.. autoclass:: numpyro.infer.svi.SVI
    :members:
    :undoc-members:
    :show-inheritance:
    :member-order: bysource

ELBO
----

.. autoclass:: numpyro.infer.elbo.ELBO
    :members:
    :undoc-members:
    :show-inheritance:
    :member-order: bysource

Trace_ELBO
----------

.. autoclass:: numpyro.infer.elbo.Trace_ELBO
    :members:
    :undoc-members:
    :show-inheritance:
    :member-order: bysource


TraceGraph_ELBO
---------------

.. autoclass:: numpyro.infer.elbo.TraceGraph_ELBO
    :members:
    :undoc-members:
    :show-inheritance:
    :member-order: bysource


TraceMeanField_ELBO
-------------------

.. autoclass:: numpyro.infer.elbo.TraceMeanField_ELBO
    :members:
    :undoc-members:
    :show-inheritance:
    :member-order: bysource

RenyiELBO
---------

.. autoclass:: numpyro.infer.elbo.RenyiELBO
    :members:
    :undoc-members:
    :show-inheritance:
    :member-order: bysource
