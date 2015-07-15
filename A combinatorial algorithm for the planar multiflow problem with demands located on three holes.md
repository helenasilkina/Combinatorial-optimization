Authors: Maxim A. Babenko, Alexander V. Karzanov

Link: http://arxiv.org/pdf/1410.7208.pdf

Abstract: We consider an undirected multi (commodity) flow demand problem in which a supply graph is planar, each source-sink pair is located on one of three specified faces of the graph, and the capacities and demands are integer-valued and Eulerian. It is known that such a problem has a solution if the cut and (2, 3)-metric conditions hold, and that the solvability implies the existence of an integer solution. We develop a purely combinatorial strongly polynomial solution algorithm.

Among a variety of multi(commodity)flow problems, one popular class embraces multiflow demand problems in undirected planar graphs in which the demand pairs are located within specified faces of the graph. More precisely, a problem input consists of: a planar graph G = (V, E) with a fixed embedding in the plane; nonnegative integer capacities c(e) ∈ Z+ of edges e ∈ E; a subset H ⊆ FG of faces, called holes (where FG is the set of faces of G); a set D of pairs st of vertices such that both s, t are located on (the boundary of) one of the holes; and demands d(st) ∈ Z+ for st ∈ D. A  multiflow for G, D is meant to be a pair f = (P, λ) consisting of a set P of D-paths P in G and nonnegative real weights λ(P) ∈ R+. Here a path P is called a D-path if
{sP , tP } = {s, t} for some st ∈ D, where sP and tP are the first and last vertices of P, respectively. We call f admissible for c, d if it satisfies the capacity constraints: 
                                                 Sum( λ(P): e ∈ P ∈ P)≤ c(e), e ∈ E, 
and realizes the demands:
                          Sum(λ(P): P ∈ P, {Sp , Tp } = {S, T} )= d(ST), ST ∈ D.
