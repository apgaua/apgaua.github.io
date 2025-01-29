---
title: Unravelling kubectl
date: 2025-01-29
author: Apgaua S
description: Resumo de como o kubectl interage com o kube-apiserver, englobando autenticação em multi contextos e k9s.
isStarred: true
---
O que é kube-apiserver

O que é kubectl

Utilizando curl para gerenciar kube-apiserver

Porque precisamos do kubectl, por que ele é melhor?

Destrinchando arquivo kube config
    Contexto, usuário, certificado

Autenticando com kube-apiserver (sem config)

Como pegar informaçoes do kubeconfig no cluster

Autenticando com kube-apiserver agora com o devido kubeconfig
    k get nodes, pods, namespaces...

E se tivermos mais de um cluster/contexto?
    Adicionando novos contextos ao kubeconfig
    Contexto default
    kubectl change context
        k get nodes, pods, namespaces....

Finalizando kubectl
    Alias e autocomplete

Gerenciamento mais fácil:   k9s
                            k9s --context