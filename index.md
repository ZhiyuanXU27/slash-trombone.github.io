# Pink trombone audios

#### Authors: Mateo Cámara, Zhiyuan Xu, Yisu Zong, and David Südholt.

#### Abstract: The abstract...

## Pink Trombone audios without variation (3.2.1)

Reference audio:


<audio controls=""> 
    <source src="audio/1_step_ref.wav">
</audio>

Produced audio after optimization:

<audio controls=""> 
    <source src="audio/1_step_pred.wav">
</audio>


## Pink Trombone audios without variation with Gaussian Noise (3.2.2)

PLEASE MIND THE VOLUME, IT COULD BE VERY LOUD

<div class="figure">
    <table>
        <tbody><tr>
            <th>SNR (dB)</th>
            <th>Original Audio</th>
            <th>Produced Audio after optimization</th>
        </tr>
        <tr>
            <td><b>inf</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/1_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/1_step_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>10</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/10db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/10db_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>0</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/1db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/1db_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>-10</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/-10db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/-10db_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>-20</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/-20db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/-20db_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>-30</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/-30db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/-30db_pred.wav">
                </audio>
            </td>
        </tr>
    </tbody>
</table>
</div>

## Pink Trombone audios with variation (3.2.3)

<div class="figure">
    <table>
        <tbody><tr>
            <th>Steps</th>
            <th>Original Audio</th>
            <th>Produced Audio after optimization</th>
        </tr>
        <tr>
            <td><b>1</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/1_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/1_step_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>2</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/2_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/2_step_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>3</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/3_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/3_step_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>10</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/10_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/10_step_pred.wav">
                </audio>
            </td>
        </tr>
    </tbody>
</table>
</div>

## Real audios (3.2.3)
<div class="figure">
    <table>
        <tbody>
        <tr>
            <th>Sample Name</th>
            <th>Orig</th>
            <th>GA</th>
            <th>PSO</th>
            <th>TRF</th>
            <th>NM</th>
            <th>CMA-ES</th>
            <th>NN</th>
        </tr>
        
        <tr>
            <td>Vowel /a/</td>
            <td>
                <audio controls>
                    <source src="./orig/a.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                    <source src="./results_real_all_wav2/a_gen_mel.wav" type="audio/mpeg">
                </audio>
                mfcc: <audio controls>
                    <source src="./results_real_all_wav2/a_gen_mfcc.wav" type="audio/mpeg">
                </audio>
                stft: <audio controls>
                    <source src="./results_real_all_wav2/a_gen_stft.wav" type="audio/mpeg">
                </audio>
                multi: <audio controls>
                    <source src="./results_real_all_wav2/a_gen_multiscale.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                    <source src="./results_real_all_wav2/a_pso_mel.wav" type="audio/mpeg">
                </audio>
                mfcc: <audio controls>
                    <source src="./results_real_all_wav2/a_pso_mfcc.wav" type="audio/mpeg">
                </audio>
                stft: <audio controls>
                    <source src="./results_real_all_wav2/a_pso_stft.wav" type="audio/mpeg">
                </audio>
                multi: <audio controls>
                    <source src="./results_real_all_wav2/a_pso_multiscale.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                    <source src="./results_real_all_wav2/a_levenberg-marquardt_mel.wav" type="audio/mpeg">
                </audio>
                mfcc: <audio controls>
                    <source src="./results_real_all_wav2/a_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
                </audio>
                stft: <audio controls>
                    <source src="./results_real_all_wav2/a_levenberg-marquardt_stft.wav" type="audio/mpeg">
                </audio>
                multi: <audio controls>
                    <source src="./results_real_all_wav2/a_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                    <source src="./results_real_all_wav2/a_downhill_mel.wav" type="audio/mpeg">
                </audio>
                mfcc: <audio controls>
                    <source src="./results_real_all_wav2/a_downhill_mfcc.wav" type="audio/mpeg">
                </audio>
                stft: <audio controls>
                    <source src="./results_real_all_wav2/a_downhill_stft.wav" type="audio/mpeg">
                </audio>
                multi: <audio controls>
                    <source src="./results_real_all_wav2/a_downhill_multiscale.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                    <source src="./results_real_all_wav2/a_cma-es_mel.wav" type="audio/mpeg">
                </audio>
                mfcc: <audio controls>
                    <source src="./results_real_all_wav2/a_cma-es_mfcc.wav" type="audio/mpeg">
                </audio>
                stft: <audio controls>
                    <source src="./results_real_all_wav2/a_cma-es_stft.wav" type="audio/mpeg">
                </audio>
                multi: <audio controls>
                    <source src="./results_real_all_wav2/a_cma-es_multiscale.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                    <source src="./results_real_all_wav2/a_nn_mel.wav" type="audio/mpeg">
                </audio>
                mfcc: <audio controls>
                    <source src="./results_real_all_wav2/a_nn_mfcc.wav" type="audio/mpeg">
                </audio>
                stft: <audio controls>
                    <source src="./results_real_all_wav2/a_nn_stft.wav" type="audio/mpeg">
                </audio>
                multi: <audio controls>
                    <source src="./results_real_all_wav2/a_nn_multiscale.wav" type="audio/mpeg">
                </audio>
            </td>
        </tr>

        <tr>
            <td>Vowel /i/</td>
            <td>
                <audio controls>
                    <source src="./orig/i.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/i_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/i_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/i_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/i_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/i_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/i_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/i_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/i_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/i_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/i_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/i_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/i_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/i_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/i_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/i_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/i_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/i_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/i_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/i_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/i_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/i_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/i_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/i_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/i_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Vowel /u/</td>
            <td>
                <audio controls>
                    <source src="./orig/u.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/u_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/u_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/u_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/u_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/u_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/u_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/u_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/u_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/u_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/u_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/u_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/u_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/u_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/u_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/u_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/u_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/u_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/u_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/u_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/u_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/u_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/u_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/u_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/u_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Vowel /e/</td>
            <td>
                <audio controls>
                    <source src="./orig/e.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/e_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/e_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/e_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/e_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/e_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/e_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/e_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/e_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/e_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/e_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/e_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/e_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/e_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/e_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/e_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/e_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/e_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/e_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/e_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/e_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/e_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/e_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/e_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/e_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Vowel /o/</td>
            <td>
                <audio controls>
                    <source src="./orig/o.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/o_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/o_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/o_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/o_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/o_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/o_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/o_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/o_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/o_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/o_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/o_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/o_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/o_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/o_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/o_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/o_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/o_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/o_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/o_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/o_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/o_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/o_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/o_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/o_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Yawn 1</td>
            <td>
                <audio controls>
                    <source src="./orig/yawn1.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn1_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn1_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn1_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn1_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn1_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn1_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn1_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn1_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn1_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn1_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn1_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn1_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn1_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn1_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn1_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn1_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn1_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn1_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn1_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn1_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn1_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn1_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn1_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn1_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Yawn 2</td>
            <td>
                <audio controls>
                    <source src="./orig/yawn2.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn2_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn2_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn2_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn2_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn2_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn2_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn2_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn2_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn2_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn2_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn2_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn2_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn2_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn2_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn2_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn2_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn2_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn2_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn2_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn2_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn2_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn2_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn2_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn2_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Yawn 3</td>
            <td>
                <audio controls>
                    <source src="./orig/yawn3.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn3_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn3_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn3_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn3_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn3_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn3_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn3_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn3_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn3_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn3_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn3_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn3_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn3_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn3_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn3_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn3_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn3_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn3_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn3_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn3_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn3_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn3_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn3_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn3_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Yawn 4</td>
            <td>
                <audio controls>
                    <source src="./orig/yawn4.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn4_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn4_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn4_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn4_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn4_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn4_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn4_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn4_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn4_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn4_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn4_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn4_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn4_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn4_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn4_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn4_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn4_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn4_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn4_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn4_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn4_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn4_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn4_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn4_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Yawn 5</td>
            <td>
                <audio controls>
                    <source src="./orig/yawn5.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn5_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn5_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn5_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn5_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn5_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn5_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn5_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn5_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn5_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn5_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn5_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn5_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn5_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn5_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn5_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn5_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn5_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn5_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn5_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn5_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn5_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn5_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn5_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn5_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Yawn 6</td>
            <td>
                <audio controls>
                    <source src="./orig/yawn6.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn6_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn6_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn6_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn6_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn6_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn6_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn6_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn6_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn6_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn6_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn6_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn6_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn6_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn6_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn6_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn6_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn6_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn6_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn6_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn6_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn6_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn6_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn6_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn6_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Yawn 7</td>
            <td>
                <audio controls>
                    <source src="./orig/yawn7.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn7_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn7_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn7_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn7_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn7_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn7_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn7_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn7_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn7_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn7_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn7_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn7_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn7_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn7_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn7_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn7_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn7_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn7_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn7_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn7_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn7_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn7_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn7_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn7_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>

        <tr>
            <td>Yawn 8</td>
            <td>
                <audio controls>
                    <source src="./orig/yawn8.wav" type="audio/mpeg">
                </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn8_gen_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn8_gen_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn8_gen_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn8_gen_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn8_pso_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn8_pso_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn8_pso_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn8_pso_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn8_levenberg-marquardt_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn8_levenberg-marquardt_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn8_levenberg-marquardt_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn8_levenberg-marquardt_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn8_downhill_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn8_downhill_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn8_downhill_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn8_downhill_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn8_cma-es_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn8_cma-es_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn8_cma-es_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn8_cma-es_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
            <td>
                mel: <audio controls>
                <source src="./results_real_all_wav2/yawn8_nn_mel.wav" type="audio/mpeg">
            </audio>
                mfcc: <audio controls>
                <source src="./results_real_all_wav2/yawn8_nn_mfcc.wav" type="audio/mpeg">
            </audio>
                stft: <audio controls>
                <source src="./results_real_all_wav2/yawn8_nn_stft.wav" type="audio/mpeg">
            </audio>
                multi: <audio controls>
                <source src="./results_real_all_wav2/yawn8_nn_multiscale.wav" type="audio/mpeg">
            </audio>
            </td>
        </tr>
        </tbody>
    </table>
</div>
