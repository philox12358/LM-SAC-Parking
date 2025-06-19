# Reinforcement_Learning_Parking_LM-SAC
Paper: Advancing Narrow Space Parking with Latent Memory-Based Reinforcement Learning

Conference: The IEEE INTELLIGENT VEHICLES SYMPOSIUM ([IV 2025](https://ieee-iv.org/2025/))

### Method Display

<div align="center">
  <img src="./imgs/Our method.gif" alt="gif" width="450">
</div>

### Contributions
- A Latent Memory-Based Soft Actor-Critic (LM-SAC)
algorithm was proposed, which leverages latent memory
to implicitly store contextual information during the park-
ing process, enabling the agent to precisely maneuver in
confined spaces.
- A Progressive Milestone Training (PMT) method is de-
veloped that decomposes the task into a series of inter-
mediate subtasks and integrates curriculum learning to
enhance the training efficiency.
- A customized virtual parking environment tailored for
narrow spaces was proposed. Surrounding obstacle in-
formation is encoded using Virtual-LiDAR Detection
(VLD), which significantly reduces the input dimension-
ality and is compatible with various perception formats.




### Performance in several different scenarios
<div align="center">
  <img src="./imgs/9.gif" alt="gif" width="450">
</div>


### Comparison with Hybrid A*
<table>
  <tr>
    <td align="center"> <img src="./imgs/" width="300" alt="img"> </td>
    <td align="center"> <img src="./imgs/" width="300" alt="img"> </td>
    <td align="center"> <img src="./imgs/" width="300" alt="img"> </td>
  </tr>
  <tr>
    <td align="center">NiuBe!</td>
    <td align="center">NiuBe!</td>
    <td align="center">NiuBe!</td>
  </tr>
</table>



