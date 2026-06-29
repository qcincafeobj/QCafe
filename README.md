# QCafe

## Installation

### Install CafeOBJ - A formal specification language

Version `1.6.2` is recommended.

Installation options:

- [Download from CafeOBJ homepage](https://cafeobj.org/)

- [Homebrew](https://brew.sh/):

    ```
    brew install cafeobj
    ```

- [Build from source (GitHub)](https://github.com/CafeOBJ/cafeobj)

### Install QCafe

- Clone this repository:

    ```
    git clone https://github.com/qcincafeobj/QCafe.git
    ```

- or Download a release:

    | Release | Publication | Authors | Notes |
    | :-: | :-: | :-: | :-: |
    | [version 1 build 2.3.5](https://github.com/qcincafeobj/QCafe/releases/tag/QCafe1) (latest) | QCafe: An Algebraic Specification of Quantum Computation and Its Application (To Appear) | **Vuong Quoc Pham**, [Canh Minh Do](https://canhminhdo.github.io), and [Kazuhiro Ogata](https://www.jaist.ac.jp/english/laboratory/cs/ogata.html) | In [SEKE2026](https://ksiresearch.org/seke/seke26.html). <br>DOI/BibTeX are at [release tag](https://github.com/qcincafeobj/QCafe/releases/tag/QCafe1). |
    | -[]() | - | - | - |



## Example Usage

Steps to verify the $n$-hop Quantum Teleportation protocol:

1. Navigate to its parent directory:

    ```
    cd QCafe/case-study
    ```


2. Start CafeOBJ:
    
    ```
    cafeobj
    ```

3. Run the file `n-hop-teleport.cafe`:

    ```
    in n-hop-teleport
    ```

    or
    ```
    in n-hop-teleport.cafe
    ```

## Repository Structure

| File/Folder | Description |
| :-: | --- |
| [qc.cafe](./qc.cafe) | Reasoning about complex number and quantum computation |
| [case-study](./case-study/) | Specification and CafeOBJ proof scores for case studies |
| [releases](./releases/) | All released versions |
| [.deprecated](./.deprecated/) | Development histories |